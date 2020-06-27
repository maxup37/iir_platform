# Red Team Automation TTPs (KO)
여기는 [endgameinc/RTA/red_ttp](https://github.com/endgameinc/RTA/tree/master/red_ttp)가 한글 윈도우에서 잘 동작하지 않는 문제를 해결한 버전을 제공합니다. (참조한 원본의 최종 수정일: 18 Aug 2018)

## Contributors
* maxKim
* air83
* asch0712
* idk3669

## Change History
|Command |Change(Y/N)|Reviewer|
|:---------------------|:-------------------------:|:--------------------:|
|at_command.py | Y|maxKim|
|certutil_file_obfuscation.py | N|idk3669|
|certutil_webrequest.py | Y|idk3669|
|common.py | N|idk3669|
|delete_catalogs.py | N|idk3669|
|delete_usnjrnl.py | N|idk3669|
|delete_volume_shadows.py | N|idk3669|
|disable_windows_fw.py | N|idk3669|
|enum_commands.py | N|idk3669|
|findstr_pw_search.py | N|idk3669|
|installutil_network.py | N|idk3669|
|lateral_commands.py | N|idk3669|
|msbuild_network.py | N|idk3669|
|mshta_network.py | N|idk3669|
|msiexec_http_installer | N|asch0712|
|msxsl_network | N|asch0712|
|net_user_add | N|asch0712|
|office_application_startup | N|asch0712|
|persistent_scripts | N|asch0712|
|powershell_args | N|asch0712|
|process_extension_anomalies | N|asch0712|
|process_name_masquerade | N|asch0712|
|recycle_bin_process | N|asch0712|
|registry_hive_export | N|asch0712|
|registry_persistence_create | N|asch0712|
|regsvr32_scrobj| N|asch0712|
|rundll32_inf_callback| N|asch0712|
|rundll32_ordinal| Y|asch0712|
|schtask_escalation| N|air83|
|scrobj_com_hijack| N|air83|
|sip_provider| Y|air83|
|smb_connection| N|air83|
|suspicious_office_children| N|air83|
|system_restore_process| N|air83|
|trust_provider| Y|air83|
|uac_eventviewer| N|air83|
|uac_sdclt| N|air83|
|unusual_ms_tool_network| N|air83|
|unusual_process_path| N|air83|
|user_dir_escalation| N|air83|
|wevtutil_log_clear| N|air83|
|wmi_tool_execution| N|air83|
