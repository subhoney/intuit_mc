gantt
    title Azure Replatform and Data Migration

    section Azure Migration - SBX
    Infrastructure Build Out (static)           :a1, 2022-06-25, 1w
    Infrastructure Acceptance Test (static)     :a2, after a1, 1w
    Setting/Config/Code changes (dynamic)       :a3, after a2, 5.5w
    E2E validation (and fix)  (static)          :a4, after a3, 3w

    section Azure Migration - DEV
    Infrastructure Build Out (static)           :b1, after a4, 1w
    Infrastructure Acceptance Test (static)     :b2, after b1, 1w
    Setting/Config/Code changes (dynamic)       :b3, after b2, 4w
    E2E validation (and fix) (static)           :b4, after b3, 3w

    section Azure Migration - STG US
    Infrastructure Build Out (static)           :c1, after b4, 1w
    Infrastructure Acceptance Test (static)     :c2, after c1, 1w
    Setting/Config/Code changes (dynamic)       :c3, after c2, 5w
    E2E validation (and fix)  (static)          :c4, after c3, 3w

    section Azure Migration - PRD US
    Infrastructure Build Out (static)           :d1, after c4, 1w
    Infrastructure Acceptance Test (static)     :d2, after d1, 1w
    Setting/Config/Code changes (dynamic)       :d3, after d2, 5w
    E2E validation (and fix)  (static)          :d4, after d3, 3w

    section Azure: Deployment US
    Operational Insights (static)               :e1, after d4, 1w
    Build Implementation plan/Cutover (static)  :e2, after e1, 1w
    Ensure Point-in-time-restore capability (static) (BCDR) :e3, after e2, 1w
    Regression Testing (static)                 :e4, after e3, 1w
    Remediate Information Security Findings     :e5, after e4, 1w
    Create External Activity                    :e6, after e5, 1w

    section Azure Migration - STG UK
    Infrastructure Build Out (static)           :f1, after e6, 1w
    Infrastructure Acceptance Test (static)     :f2, after f1, 1w
    Setting/Config/Code changes (dynamic)       :f3, after f2, 5w
    E2E validation (and fix)  (static)          :f4, after f3, 3w

    section Azure Migration - PRD UK
    Infrastructure Build Out (static)           :g1, after f4, 1w
    Infrastructure Acceptance Test (static)     :g2, after g1, 1w
    Setting/Config/Code changes (dynamic)       :g3, after g2, 5w
    E2E validation (and fix)  (static)          :g4, after g3, 3w

    section Azure: Deployment UK
    Operational Insights (static)               :h1, after g4, 1w
    Build Implementation plan/Cutover (static)  :h2, after h1, 1w
    Ensure Point-in-time-restore capability (static) :h3, after h2, 1w
    Regression Testing (static)                 :h4, after h3, 1w
