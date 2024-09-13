| Severity       | Facility               | Mnemonics                                                                                                                              |
| ------------- | --------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| 0 - Emergency  | CI                     | SHUT_LC_FANGONE, SHUTFANGONE, SHUTFANFAIL, SHUT_LC_FANFAIL                                                                             |
| 1 - Alert      | PLATFORM_ENV           | FRU_PS_FAN_FAILED, RPS_FAN_FAILED, FRU_PS_FAN_OK, FAN, FAN_NOT_PRESENT, FRU_FAN_OK, PLATFORM_FAN_CRITICAL, RPS_PS_FAN_FAILED           |
| 1 - Alert      | PLATFORM_THERMAL       | FRU_FAN_FAILURE, FRU_FAN_RECOVERY, FAN_CRITICAL, FRU_FAN_NOT_PRESENT, FRU_FAN_DISABLED, FRU_FAN_INSUFFICIENTFANTRAYSDETECTEDPOWERDOWN  |
| 1 - Alert      | PLATFORM_FEP           | FRU_PS_SIGNAL_FAULTY                                                                                                                   |
| 1 - Alert      | ENVMON                 | RPS_FAN_FAILED                                                                                                                         |
| 1 - Alert      | CI                     | FAN_FAILURE_LC_SHUT, FAN_MISSING, TOTALFANFAIL, NOFAN                                                                                  |
| 1 - Alert      | HARDWARE               | THERMAL_CRITICAL                                                                                                                       |
| 1 - Alert      | SYS                    | OVERTEMP                                                                                                                               |
| 1 - Alert      | ENVM                   | OVERTEMP_ALERT                                                                                                                         |
| 1 - Alert      | PLATFORM               | PFM_ALERT                                                                                                                              |
| 1 - Alert      | CMRP_PFU               | PFU_FAN_FAILED                                                                                                                         |
| 2 - Critical   | C4K_IOSMODPORTMAN      | MODULECRITICALTEMP, CRITICALTEMP                                                                                                       |
| 2 - Critical   | CTS                    | AUTHZ_POLICY_SGACL_ACE_FAILED                                                                                                          |
| 2 - Critical   | THERMAL                | THERMAL_YELLOW_THRESHOLD, THERMAL_RED_THRESHOLD                                                                                        |
| 2 - Critical   | SPA                    | TEMP_CRITICAL                                                                                                                          |
| 2 - Critical   | IOSXE_RP_ALARM         | PEM                                                                                                                                    |
| 2 - Critical   | ENV_MON                | FANOK, FAN                                                                                                                             |
| 2 - Critical   | ENVIRONMENT            | FAN_FAULT                                                                                                                              |
| 2 - Critical   | PLATFORM               | PS_RED_MODE_CHG, PS_FAIL, PS_DETECT, PS_ABSENT                                                                                         |
| 2 - Critical   | SPANTREE               | LOOPGUARD_BLOCK, ROOTGUARDBLOCK                                                                                                        |
| 2 - Critical   | C6KENV                 | MAJORTEMPALARM, MAJORTEMPALARM                                                                                                         |
| 3 - Error      | CMRP_ENVMON            | TEMP_SYS_SHUTDOWN_PENDING, TEMP_WARN_CRITICAL, TEMP_FRU_SHUTDOWN_PENDING                                                               |
| 3 - Error      | CI                     | PARTIAL_FAN_FAIL, PARTFANFAIL, PSFANFAIL                                                                                               |
| 3 - Error      | RADIUS                 | ALLDEADSERVER                                                                                                                          |
| 3 - Error      | WLANMGR_TRACE_MESSAGE  | EWLC_WLANMGR_SCHEDULED_WLAN_DISABLE, EWLC_WLANMGR_SCHEDULED_WLAN_ENABLE                                                                |
| 3 - Error      | CMRP_PFU               | PWR_MGMT_LC_SHUTDOWN, PWR_MGMT_ALARM                                                                                                   |
| 3 - Error      | ENVM                   | FAN_FAILED, FAN_OK_ERR, FAN_FAILED_ERR, FAN_ON, FAN_RECOVERED, FAN_SHUTDOWN_ERR                                                        |
| 3 - Error      | LINK                   | UPDOWN                                                                                                                                 |
| 3 - Error      | RMGR                   | RED_WLC_SWITCHOVER, RED_HEARTBEAT_TMOUT                                                                                                |
| 3 - Error      | ILPOWER                | SHUT_OVERDRAWN, CONTROLLER_PORT_ERR, CONTROLLER_ERR                                                                                    |
| 3 - Error      | HARDWARE               | THERMAL_NOT_FUNCTIONING                                                                                                                |
| 4 - Warning    | MM                     | MEMBER_DOWN, MEMBER_UP                                                                                                                 |
| 4 - Warning    | RADIUS                 | RADIUS_ALIVE, RADIUS_DEAD                                                                                                              |
| 4 - Warning    | MAC_LIMIT              | PORT_EXCEED, VLAN_EXCEED                                                                                                               |
| 4 - Warning    | PLATFORM_STACKPOWER    | INSUFFICIENT_PWR, TOO_MANY_ERRORS, UNDER_BUDGET, VERSION_MISMATCH, REDUNDANCY_LOSS                                                     |
| 4 - Warning    | CMRP_PFU               | PFU_FAN_WARN                                                                                                                           |
| 4 - Warning    | SW_MATM                | MACFLAP_NOTIF                                                                                                                          |
| 4 - Warning    | C4K_IOSMODPORTMAN      | MODULETEMPHIGH, MODULECRITICALTEMP, TEMPHIGH, CRITICALTEMP                                                                             |
| 4 - Warning    | LISP                   | CEF_DISABLED, LOCAL_EID_MAP_REGISTER_FAILURE, LOCAL_EID_NO_ROUTE, LOCAL_EID_RLOC_INCONSISTENCY, MAP_CACHE_WARNING_THRESHOLD_REACHED    |
| 4 - Warning    | C6KENV                 | TERMINATOR_PS_TEMP_MAJORALARM, TERMINATOR_PS_TEMP_MAJORALARM                                                                           |
| 4 - Warning    | CDP                    | DUPLEX_MISMATCH, NATIVE_VLAN_MISMATCH                                                                                                  |
| 5 - Notice     | SFF8472                | THRESHOLD_VIOLATION                                                                                                                    |
| 5 - Notice     | PORT                   | IF_UP, IF_DOWN                                                                                                                         |
| 5 - Notice     | LINK                   | CHANGED                                                                                                                                |
| 5 - Notice     | SPANTREE               | ROOTCHANGE                                                                                                                             |
| 5 - Notice     | ENVIRONMENTAL          | SENSOROK                                                                                                                               |
| 5 - Notice     | SYS                    | RESTART, RELOAD, CONFIG_I                                                                                                              |
| 5 - Notice     | DOT1X                  | SUCCESS, FAIL                                                                                                                          |
| 5 - Notice     | IFDAMP                 | UPDOWN                                                                                                                                 |
| 5 - Notice     | AUTHMGR                | START, SUCCESS                                                                                                                         |
| 5 - Notice     | CLNS                   | ADJCHANGE                                                                                                                              |
| 6 - Info       | PLATFORM_STACKPOWER    | LINK_EVENT, CABLE_EVENT                                                                                                                |
| 6 - Info       | IOSXE_OIR              | OFFLINECARD                                                                                                                            |
| 6 - Info       | SPA_OIR                | OFFLINECARD                                                                                                                            |
| 6 - Info       | SYS                    | INTF_STATUS_CHANGE                                                                                                                     |
| 6 - Info       | OIR                    | INSCARD, INSCARD, REMCARD, REMCARD                                                                                                     |
| 6 - Info       | CMCC                   | MGMT_SFP_REMOVED, MGMT_SFP_INSERT                                                                                                      |
| 6 - Info       | PLATFORM               | HASTATUS_DETAIL, HASTATUS                                                                                                              |
| 6 - Info       | STACKMGR               | STACK_LINK_CHANGE                                                                                                                      |
| 6 - Info       | SISF                   | ENTRY_CREATED                                                                                                                          |
| 6 - Info       | ENV_MON                | REMPEM                                                                                                                                 |
