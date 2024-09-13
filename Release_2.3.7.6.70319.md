| Severity       | Facility                     | Mnemonics                                                                                                                              |
| ------------- | --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| 0 - Emergency  | CI                           | SHUT_LC_FANGONE, SHUTFANGONE, SHUTFANFAIL, SHUT_LC_FANFAIL                                                                             |
| 1 - Alert      | PLATFORM_ENV                 | FRU_PS_FAN_FAILED, RPS_FAN_FAILED, FRU_PS_FAN_OK, FAN, FAN_NOT_PRESENT, FRU_FAN_OK, PLATFORM_FAN_CRITICAL, RPS_PS_FAN_FAILED           |
| 1 - Alert      | PLATFORM_THERMAL             | FRU_FAN_FAILURE, FRU_FAN_RECOVERY, FAN_CRITICAL, FRU_FAN_NOT_PRESENT, FRU_FAN_DISABLED, FRU_FAN_INSUFFICIENTFANTRAYSDETECTEDPOWERDOWN  |
| 1 - Alert      | PLATFORM_FEP                 | FRU_PS_SIGNAL_FAULTY                                                                                                                   |
| 1 - Alert      | ENVMON                       | RPS_FAN_FAILED                                                                                                                         |
| 1 - Alert      | CI                           | FAN_FAILURE_LC_SHUT, FAN_MISSING, TOTALFANFAIL, NOFAN                                                                                  |
| 1 - Alert      | HARDWARE                     | THERMAL_CRITICAL                                                                                                                       |
| 1 - Alert      | SYS                          | OVERTEMP                                                                                                                               |
| 1 - Alert      | ENVM                         | OVERTEMP_ALERT                                                                                                                         |
| 1 - Alert      | PLATFORM                     | PFM_ALERT                                                                                                                              |
| 1 - Alert      | CMRP_PFU                     | PFU_FAN_FAILED                                                                                                                         |
| 2 - Critical   | C4K_IOSMODPORTMAN            | MODULECRITICALTEMP, CRITICALTEMP                                                                                                       |
| 2 - Critical   | CTS                          | AUTHZ_POLICY_SGACL_ACE_FAILED                                                                                                          |
| 2 - Critical   | THERMAL                      | THERMAL_YELLOW_THRESHOLD, THERMAL_RED_THRESHOLD                                                                                        |
| 2 - Critical   | SPA                          | TEMP_CRITICAL                                                                                                                          |
| 2 - Critical   | IOSXE_RP_ALARM               | PEM                                                                                                                                    |
| 2 - Critical   | ENV_MON                      | FANOK, FAN                                                                                                                             |
| 2 - Critical   | ENVIRONMENT                  | FAN_FAULT                                                                                                                              |
| 2 - Critical   | PLATFORM                     | PS_RED_MODE_CHG, PS_FAIL, PS_DETECT, PS_ABSENT                                                                                         |
| 2 - Critical   | SPANTREE                     | BLOCK_BPDUGUARD                                                                                                                        |
| 2 - Critical   | C6KENV                       | MAJORTEMPALARM                                                                                                                         |
| 3 - Error      | SFF8472                      | THRESHOLD_VIOLATION                                                                                                                    |
| 3 - Error      | WLANMGR_TRACE_MESSAGE        | EWLC_WLANMGR_SCHEDULED_WLAN_DISABLE, EWLC_WLANMGR_SCHEDULED_WLAN_ENABLE                                                                |
| 3 - Error      | POWER_SUPPLIES               | PWR_FAIL                                                                                                                               |
| 3 - Error      | CLIENT_ORCH_AUDIT_MESSAGE    | FIPS_AUDIT_FTA_TSE1_DENY_CLIENT_ACCESS                                                                                                 |
| 3 - Error      | BGP                          | NOTIFICATION                                                                                                                           |
| 3 - Error      | REDUNDANCY                   | PEER_MONITOR, SWITCHOVER, STANDBY_LOST                                                                                                 |
| 3 - Error      | CI                           | PARTIAL_FAN_FAIL, PARTFANFAIL, PSFANFAIL                                                                                               |
| 3 - Error      | STANDBY                      | DUPADDR                                                                                                                                |
| 3 - Error      | IOSXE_PEM                    | PEMCHASFSERR, PEMFAIL, FAN_FAIL_SHUTDOWN, FANFAIL                                                                                      |
| 3 - Error      | CMRP_ENVMON                  | TEMP_SYS_SHUTDOWN_PENDING, TEMP_WARN_CRITICAL, TEMP_FRU_SHUTDOWN_PENDING                                                               |
| 4 - Warning    | LISP                         | MAP_CACHE_WARNING_THRESHOLD_REACHED, LOCAL_EID_NO_ROUTE, LOCAL_EID_MAP_REGISTER_FAILURE, CEF_DISABLED, LOCAL_EID_RLOC_INCONSISTENCY    |
| 4 - Warning    | PM                           | ERR_DISABLE                                                                                                                            |
| 4 - Warning    | PLATFORM_STACKPOWER          | UNDER_BUDGET, VERSION_MISMATCH, TOO_MANY_ERRORS, INSUFFICIENT_PWR, REDUNDANCY_LOSS                                                     |
| 4 - Warning    | UDLD                         | UDLD_PORT_DISABLED                                                                                                                     |
| 4 - Warning    | IP                           | DUPADDR                                                                                                                                |
| 4 - Warning    | SW_MATM                      | MACFLAP_NOTIF                                                                                                                          |
| 4 - Warning    | CMRP_PFU                     | PFU_FAN_WARN                                                                                                                           |
| 4 - Warning    | C4K_IOSMODPORTMAN            | MODULETEMPHIGH, POWERSUPPLYBAD, CRITICALTEMP, MODULECRITICALTEMP, TEMPHIGH, FANTRAYREMOVED                                             |
| 4 - Warning    | C6KENV                       | TERMINATOR_PS_TEMP_MAJORALARM                                                                                                          |
| 4 - Warning    | MAC_MOVE                     | NOTIF                                                                                                                                  |
| 5 - Notice     | SFF8472                      | THRESHOLD_VIOLATION                                                                                                                    |
| 5 - Notice     | DUAL                         | NBRCHANGE                                                                                                                              |
| 5 - Notice     | DMI                          | SYNC_NEEDED, SYNC_START                                                                                                                |
| 5 - Notice     | BGP                          | ADJCHANGE                                                                                                                              |
| 5 - Notice     | REDUNDANCY                   | PEER_MONITOR_EVENT                                                                                                                     |
| 5 - Notice     | IFDAMP                       | UPDOWN                                                                                                                                 |
| 5 - Notice     | CAPWAPAC_SMGR_TRACE_MESSAGE  | AP_JOIN_DISJOIN                                                                                                                        |
| 5 - Notice     | OSPF                         | ADJCHG                                                                                                                                 |
| 5 - Notice     | DOT1X                        | SUCCESS, FAIL                                                                                                                          |
| 5 - Notice     | ILPOWER                      | ILPOWER_POWER_DENY                                                                                                                     |
| 6 - Info       | IOSXE_OIR                    | REMSPA, INSSPA, OFFLINECARD                                                                                                            |
| 6 - Info       | TRANSCEIVER                  | REMOVED, INSERTED                                                                                                                      |
| 6 - Info       | SMART_LIC                    | AGENT_READY, HA_ROLE_CHANGED, AGENT_ENABLED                                                                                            |
| 6 - Info       | STANDBY                      | STATECHANGE                                                                                                                            |
| 6 - Info       | IOSXE_PEM                    | REMPEM_FM, FANOK, PEMOK                                                                                                                |
| 6 - Info       | PLATFORM_STACKPOWER          | CABLE_EVENT, LINK_EVENT                                                                                                                |
| 6 - Info       | ENV_MON                      | REMPEM                                                                                                                                 |
| 6 - Info       | PLATFORM                     | HASTATUS_DETAIL, HASTATUS                                                                                                              |
| 6 - Info       | IOSXE_INFRA                  | PROCPATH_CLIENT_HOG                                                                                                                    |
| 6 - Info       | STACKMGR                     | STACK_LINK_CHANGE                                                                                                                      |
