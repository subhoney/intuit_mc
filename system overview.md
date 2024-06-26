graph TD;

A[Web App] <-->|HTTP requests| B(API Gateway/Load Balancer)
B <-->|Routes requests to...| C[Monolithic Codebase]
B <-->|Routes requests to...| D[Microservice]
B <-->|Routes requests to...| E[Microservice]
B <-->|Routes requests to...| F[Microservice n]
C <-->|Uses| G[(RDBMS)]
D <-->|Uses| H[(RDBMS)]
E <-->|Uses| I[(Document Data Store)]
F <-->|Uses| J[Blob Storage]
D <-->|Uses| K[[Cache]]
E <-->|Uses| L[[Cache]]
F <-->|Uses| M[[Cache]]

N((Auth Provider))
N <--> A
A <--> N