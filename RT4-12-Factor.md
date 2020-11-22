# The Twelve-Factor App

|  #  | Factor              | Description                                                                                                         | Priority |
| :-: | :------------------ | :------------------------------------------------------------------------------------------------------------------ | :------: |
| 11  | Logs                | Applications should produce logs as event streams and leave the execution environment to aggregate.                 |    1     |
|  5  | Build, release, run | The delivery pipeline should strictly consist of build, release, run.                                               |    2     |
|  1  | Codebase            | There should be exactly one codebase for a deployed service with the codebase being used for many deployments.      |    3     |
| 10  | Dev/Prod parity     | All environments should be as similar as possible.                                                                  |    4     |
|  7  | Port binding        | Self-contained services should make themselves available to other services by specified ports.                      |    5     |
|  3  | Config              | Configuration that varies between deployments should be stored in the environment.                                  |    6     |
|  4  | Backing services    | All backing services are treated as attached resources and attached and detached by the execution environment.      |    7     |
|  2  | Dependencies        | All dependencies should be declared, with no implicit reliance on system tools or libraries.                        |    8     |
| 12  | Admin Processes     | Any needed admin tasks should be kept in source control and packaged with the application.                          |    9     |
|  6  | Processes           | Applications should be deployed as one or more stateless processes with persisted data stored on a backing service. |    10    |
|  9  | Disposability       | Fast startup and shutdown are advocated for a more robust and resilient system.                                     |    11    |
|  8  | Concurrency         | Concurrency is advocated by scaling individual processes.                                                           |    12    |
