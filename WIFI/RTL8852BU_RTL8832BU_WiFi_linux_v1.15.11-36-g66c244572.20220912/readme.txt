===============================================================================
		Software Package - Component
===============================================================================
	1. ReleaseNotes.pdf

	2. document/
		2.1. Driver_Configuration_for_RF_Regulatory_Certification.pdf
		2.2. HowTo_enable_and_verify_TDLS_function_in_Wi-Fi_driver.pdf
		2.3. HowTo_enable_driver_to_support_mbo.pdf
		2.4. HowTo_enable_the_power_saving_functionality.pdf
		2.5. HowTo_support_WIFI_certification_test.pdf
		2.6. How_to_append_vendor_specific_ie_to_driver_management_frames.pdf
		2.7. How_to_set_driver_debug_log_level.pdf
		2.8. Quick_Start_Guide_for_Adaptivity_and_Carrier_Sensing_Test.pdf
		2.9. Quick_Start_Guide_for_Bridge.pdf
		2.10. Quick_Start_Guide_for_Driver_Compilation_and_Installation.pdf
		2.11. Quick_Start_Guide_for_SoftAP.pdf
		2.12. Quick_Start_Guide_for_Station_Mode.pdf
		2.13. Quick_Start_Guide_for_WOW.pdf
		2.14. Quick_Start_Guide_for_WPA3.pdf
		2.15. Quick_Start_Guide_for_wpa_supplicant_WiFi_P2P_test.pdf
		2.16. Realtek_WiFi_concurrent_mode_Introduction.pdf
		2.17. SoftAP_Mode_features.pdf
		2.18. linux_dhcp_server_notes.txt
		2.19. wpa_cli_with_wpa_supplicant.pdf

	3. driver/
		3.1. rtl8852BU_rtl8832BU_WiFi_linux_v1.15.11-36-g66c244572.20220902.tar.gz
			Naming rule: rtlCHIPS[_WiFi]_linux_vM.N.P[.H]-C-gSHA-1.yyyymmdd[_COEX_VER][_beta].tar.gz
			where:
				CHIPS: supported chips
				M: Major version
				N: miNor version
				P: Patch number
				H: Hotfix number
				C: numbers of commit
				SHA-1: sha-1 of this commit
				y: package year
				m: package month
				d: package day
				COEX_VER: Coext version
				_beta: beta driver

	4. android_ref_codes_O_8.0/
		4.1. Realtek_Wi-Fi_SDK_for_Android_O_8.0.pdf
			Guide for porting Realtek wifi onto your Android 8.0 system

		4.2. linux-3.0.42_STATION_INFO_ASSOC_REQ_IES.diff
			Kernel patch file for cfg80211's STATION_INFO_ASSOC_REQ_IES event for kernel 3.0.

		4.3. realtek_wifi_SDK_for_android_O_8.0_20200505.tar.gz
			This tar ball includes our android wifi reference codes for Android 8.0

		4.4. supplicant_overlay_config.tar.gz

	5. android_ref_codes_P_9.x/
		5.1. wpa_supplicant_8_P_9.x_rtw_r29226.20180827.tar.gz
			wpa_supplicant_8 from Android 9.x SDK and patched by Realtek
			could be used Android 9.x. Support only cfg80211/nl80211.

		5.2. Realtek_Wi-Fi_SDK_for_Android_P_9.x.pdf
			Guide for porting Realtek wifi onto your Android 9.x system

		5.3. linux-3.0.42_STATION_INFO_ASSOC_REQ_IES.diff
			Kernel patch file for cfg80211's STATION_INFO_ASSOC_REQ_IES event for kernel 3.0.

		5.4. realtek_wifi_SDK_for_android_P_9.x_20200505.tar.gz
			This tar ball includes our android wifi reference codes for Android 9.x

		5.5. supplicant_overlay_config.tar.gz
		
		5.6. wpa_supplicant_8_P_9.x_rtw_add_support_for_self-managed_regulatory_device
			wpa_supplicant_8_P_9.x_rtw patches to add support for self-managed regulatory device

	6. android_ref_codes_10.x/
		6.1. wpa_supplicant_8_10.x_rtw_29226.20200409.tar.gz
			wpa_supplicant_8 from Android 10.x SDK and patched by Realtek
			could be used Android 10.x. Support only cfg80211/nl80211.

		6.2. Realtek_Wi-Fi_SDK_for_Android_10.pdf
			Guide for porting Realtek wifi onto your Android 10.x system

		6.3. realtek_wifi_SDK_for_android_10_x_20200505.tar.gz
			This tar ball includes our android wifi reference codes for Android 10.x

		6.4. supplicant_overlay_config.tar.gz

	7. android_ref_codes_11.x/
		7.1. wpa_supplicant_8_11.0.0.r3_rtw_20201005.tar.gz
			wpa_supplicant_8 from Android 11.0 SDK and patched by Realtek
			could be used Android 11.0. Support only cfg80211/nl80211.

		7.2. Realtek_Wi-Fi_SDK_for_Android_11.pdf
			Guide for porting Realtek wifi onto your Android 11.0 system

		7.3. realtek_wifi_SDK_for_android_11_x_20210416.tar.gz
			This tar ball includes our android wifi reference codes for Android 11.0

		7.4. supplicant_overlay_config.tar.gz

	8. android_ref_codes_12.x/
		8.1. wpa_supplicant_8_android12-release_rtw_20211130.tar.gz
			wpa_supplicant_8 from Android 12.x SDK and patched by Realtek
			could be used Android 12.x. Support only cfg80211/nl80211.

		8.2. Realtek_Wi-Fi_SDK_for_Android_12.pdf
			Guide for porting Realtek wifi onto your Android 12.x system

		8.3. realtek_wifi_SDK_for_android_12_x_20211130.tar.gz
			This tar ball includes our android wifi reference codes for Android 12.x

		8.4. supplicant_overlay_config.tar.gz

	9. install.sh
		Script to compile and install WiFi driver easily in PC-Linux

	10. wpa_supplicant_hostapd/
		10.1. wpa_supplicant_8_O_8.x_rtw-17-g894b400ab.20210716.tar.gz
			wpa_supplicant_8 from Android 8.x SDK and patched by Realtek
			could be used for pure-linux and Android 8.x. Support only cfg80211/nl80211.

		10.2. hostap_2_10-rtw-9-g422792039.20220120.tar.gz
			This package includes w1.fi official wpa_supplicant and hostapd, and it is patched by Realtek.
			It can be used for pure Linux, which only supports cfg80211/nl80211.

		10.3. p2p_hostapd.conf
			Configure file for hostapd for Wi-Fi Direct (P2P)

		10.4. rtl_hostapd_2G.conf
			Configure files for Soft-AP mode 2.4G

		10.5. rtl_hostapd_5G.conf
			Configure files for Soft-AP mode 5G

==================================================================================================================
		User Guide for Driver compilation and installation
==================================================================================================================
			(*) Please refer to document/Quick_Start_Guide_for_Driver_Compilation_and_Installation.pdf
==================================================================================================================
		User Guide for Station mode
==================================================================================================================
			(*) Please refer to document/Quick_Start_Guide_for_Station_Mode.pdf
==================================================================================================================
		User Guide for Soft-AP mode
==================================================================================================================
			(*) Please refer to document/Quick_Start_Guide_for_SoftAP.pdf
			(*) Please use hostap_2_10-rtw-9-g422792039.20220120.tar.gz
			(*) Please refer to document/linux_dhcp_server_notes.txt
==================================================================================================================
		User Guide for Wi-Fi Direct
==================================================================================================================
		Wi-Fi Direct with nl80211
			(*) Please use:
					wpa_supplicant_8_O_8.x_rtw-17-g894b400ab.20210716.tar.gz
				or
					wpa_supplicant_8_P_9.x_rtw_r29226.20180827.tar.gz
				or
					wpa_supplicant_8_10.x_rtw_29226.20200409.tar.gz
				or
					wpa_supplicant_8_11.0.0.r3_rtw_20201005.tar.gz
				or
					wpa_supplicant_8_android12-release_rtw_20211130.tar.gz
			(*) For P2P instruction/command, please refer to:
					README-P2P inside the wpa_supplicant folder of the wpa_supplicant_8 you choose
			(*) For DHCP server, please refer to:
					document/linux_dhcp_server_notes.txt
==================================================================================================================
		User Guide for WPS2.0
==================================================================================================================
			(*) Please use:
					hostap_2_10-rtw-9-g422792039.20220120.tar.gz
				or
					wpa_supplicant_8_O_8.x_rtw-17-g894b400ab.20210716.tar.gz
				or
					wpa_supplicant_8_P_9.x_rtw_r29226.20180827.tar.gz
				or
					wpa_supplicant_8_10.x_rtw_29226.20200409.tar.gz
				or
					wpa_supplicant_8_11.0.0.r3_rtw_20201005.tar.gz
				or
					wpa_supplicant_8_android12-release_rtw_20211130.tar.gz
			(*) For WPS instruction/command, please refert to:
					README-WPS inside the wpa_supplicant folder of the wpa_supplicant_8 you choose
==================================================================================================================
		User Guide for Power Saving Mode
==================================================================================================================
			(*) Please refer to document/HowTo_enable_the_power_saving_functionality.pdf
==================================================================================================================
		User Guide for Applying Wi-Fi solution onto Andriod System
==================================================================================================================
			(*) For Android 8.0, please refer to android_ref_codes_O_8.0/Realtek_Wi-Fi_SDK_for_Android_O_8.0.pdf
			(*) For Android 9.x, please refer to android_ref_codes_P_9.x/Realtek_Wi-Fi_SDK_for_Android_P_9.x.pdf
			(*) For Android 10.x, please refer to android_ref_codes_10.x/Realtek_Wi-Fi_SDK_for_Android_10.pdf
			(*) For Android 11.0, please refer to android_ref_codes_11.x/Realtek_Wi-Fi_SDK_for_Android_11.pdf
			(*) For Android 12.x, please refer to android_ref_codes_12.x/Realtek_Wi-Fi_SDK_for_Android_12.pdf
==================================================================================================================
		User Guide for WPA3 Personal
==================================================================================================================
			(*) hostap_2_10-rtw-9-g422792039.20220120.tar.gz
			(*) Please refer to wpa_cli_with_wpa_supplicant.pdf
			(*) Please refer to Quick_Start_Guide_for_WPA3.pdf
