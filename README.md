---- Minecraft Crash Report ----
// Hi. I'm Minecraft, and I'm a crashaholic.

Time: 2025-02-09 01:30:08
Description: Initializing game

org.spongepowered.asm.mixin.transformer.throwables.MixinTransformerError: An unexpected critical error was encountered
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:392) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClass(MixinTransformer.java:250) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.service.modlauncher.MixinTransformationHandler.processClass(MixinTransformationHandler.java:131) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.launch.MixinLaunchPluginLegacy.processClass(MixinLaunchPluginLegacy.java:131) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at cpw.mods.modlauncher.serviceapi.ILaunchPluginService.processClassWithFlags(ILaunchPluginService.java:156) ~[modlauncher-10.0.8.jar:10.0.8+10.0.8+main.0ef7e830] {}
	at cpw.mods.modlauncher.LaunchPluginHandler.offerClassNodeToPlugins(LaunchPluginHandler.java:88) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.ClassTransformer.transform(ClassTransformer.java:120) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.TransformingClassLoader.maybeTransformClassBytes(TransformingClassLoader.java:50) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.readerToClass(ModuleClassLoader.java:113) ~[securejarhandler-2.1.6.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.lambda$findClass$15(ModuleClassLoader.java:219) ~[securejarhandler-2.1.6.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.loadFromModule(ModuleClassLoader.java:229) ~[securejarhandler-2.1.6.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.findClass(ModuleClassLoader.java:219) ~[securejarhandler-2.1.6.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.loadClass(ModuleClassLoader.java:135) ~[securejarhandler-2.1.6.jar:?] {}
	at java.lang.ClassLoader.loadClass(ClassLoader.java:525) ~[?:?] {}
	at net.minecraft.client.Minecraft.<init>(Minecraft.java:502) ~[client-1.19.4-20230314.122934-srg.jar%23234!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:iceberg.mixins.json:MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:169) ~[Cromta's%20Solo%20Leveling%20pack%20Cromta's%20Solo%20Leveling%20Modpack.jar:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$launchService$0(CommonClientLaunchHandler.java:27) ~[fmlloader-1.19.4-45.2.0.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:106) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:77) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}
Caused by: org.spongepowered.asm.mixin.throwables.ClassMetadataNotFoundException: org.jwaresoftware.mcmods.lib.api.mod.IModRuntime
	at org.spongepowered.asm.mixin.transformer.MixinPreProcessorStandard.transformMethod(MixinPreProcessorStandard.java:754) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinPreProcessorStandard.transform(MixinPreProcessorStandard.java:739) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinPreProcessorStandard.attach(MixinPreProcessorStandard.java:310) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinPreProcessorStandard.createContextFor(MixinPreProcessorStandard.java:280) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinInfo.createContextFor(MixinInfo.java:1288) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.apply(MixinApplicatorStandard.java:292) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.TargetClassContext.apply(TargetClassContext.java:383) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.TargetClassContext.applyMixins(TargetClassContext.java:365) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:363) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	... 28 more


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Stacktrace:
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:392) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClass(MixinTransformer.java:250) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.service.modlauncher.MixinTransformationHandler.processClass(MixinTransformationHandler.java:131) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.launch.MixinLaunchPluginLegacy.processClass(MixinLaunchPluginLegacy.java:131) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at cpw.mods.modlauncher.serviceapi.ILaunchPluginService.processClassWithFlags(ILaunchPluginService.java:156) ~[modlauncher-10.0.8.jar:10.0.8+10.0.8+main.0ef7e830] {}
	at cpw.mods.modlauncher.LaunchPluginHandler.offerClassNodeToPlugins(LaunchPluginHandler.java:88) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.ClassTransformer.transform(ClassTransformer.java:120) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.TransformingClassLoader.maybeTransformClassBytes(TransformingClassLoader.java:50) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.readerToClass(ModuleClassLoader.java:113) ~[securejarhandler-2.1.6.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.lambda$findClass$15(ModuleClassLoader.java:219) ~[securejarhandler-2.1.6.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.loadFromModule(ModuleClassLoader.java:229) ~[securejarhandler-2.1.6.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.findClass(ModuleClassLoader.java:219) ~[securejarhandler-2.1.6.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.loadClass(ModuleClassLoader.java:135) ~[securejarhandler-2.1.6.jar:?] {}
	at java.lang.ClassLoader.loadClass(ClassLoader.java:525) ~[?:?] {}
	at net.minecraft.client.Minecraft.<init>(Minecraft.java:502) ~[client-1.19.4-20230314.122934-srg.jar%23234!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:iceberg.mixins.json:MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:A,pl:runtimedistcleaner:A}
-- Initialization --
Details:
	Modules: 
		ADVAPI32.dll:Gelişmiş Windows 32 Tabanlı API:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		COMCTL32.dll:Kullanıcı Deneyimi Denetimleri Kitaplığı:6.10 (WinBuild.160101.0800):Microsoft Corporation
		CRYPT32.dll:Şifreleme API32:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		CRYPTBASE.dll:Base cryptographic API DLL:10.0.26100.2894 (WinBuild.160101.0800):Microsoft Corporation
		CRYPTSP.dll:Cryptographic Service Provider API:10.0.26100.2454 (WinBuild.160101.0800):Microsoft Corporation
		CoreMessaging.dll:Microsoft CoreMessaging Dll:10.0.26100.1882 (WinBuild.160101.0800):Microsoft Corporation
		CoreUIComponents.dll:Microsoft Core UI Components Dll:10.0.26100.2454:Microsoft Corporation
		DBGHELP.DLL:Windows Image Helper:10.0.26100.2033 (WinBuild.160101.0800):Microsoft Corporation
		DEVOBJ.dll:Device Information Set DLL:10.0.26100.1150 (WinBuild.160101.0800):Microsoft Corporation
		DNSAPI.dll:DNS İstemcisi API DLL'si:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		GDI32.dll:GDI Client DLL:10.0.26100.2033 (WinBuild.160101.0800):Microsoft Corporation
		GLU32.dll:OpenGL Yardımcı Uygulaması DLL Kitaplığı:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		IMM32.DLL:Multi-User Windows IMM32 API Client DLL:10.0.26100.1150 (WinBuild.160101.0800):Microsoft Corporation
		IPHLPAPI.DLL:IP Helper API:10.0.26100.2304 (WinBuild.160101.0800):Microsoft Corporation
		KERNEL32.DLL:Win32 Kernel çekirdek bileşeni:10.0.26100.2454 (WinBuild.160101.0800):Microsoft Corporation
		KERNELBASE.dll:Win32 Kernel çekirdek bileşeni:10.0.26100.2454 (WinBuild.160101.0800):Microsoft Corporation
		MMDevApi.dll:MMDevice API'sı:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		MSASN1.dll:ASN.1 Runtime APIs:10.0.26100.2894 (WinBuild.160101.0800):Microsoft Corporation
		MSCTF.dll:MSCTF Server DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		NSI.dll:NSI User-mode interface DLL:10.0.26100.2894 (WinBuild.160101.0800):Microsoft Corporation
		NTASN1.dll:Microsoft ASN.1 API:10.0.26100.1 (WinBuild.160101.0800):Microsoft Corporation
		OLEAUT32.dll:OLEAUT32.DLL:10.0.26100.1882 (WinBuild.160101.0800):Microsoft Corporation
		Ole32.dll:Windows için Microsoft OLE:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		OpenAL.dll:Main implementation library:1.21.1:
		POWRPROF.dll:Güç Profili Yardımcısı DLL'si:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		PSAPI.DLL:Process Status Helper:10.0.26100.1 (WinBuild.160101.0800):Microsoft Corporation
		Pdh.dll:Windows Performance Data Helper DLL:10.0.26100.2304 (WinBuild.160101.0800):Microsoft Corporation
		RPCRT4.dll:Uzaktan Yordam Çağrısı Çalıştırma Zamanı Modülü:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		SHCORE.dll:SHCORE:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		SHELL32.dll:Windows Shell Ortak Dll'i:10.0.26100.2454 (WinBuild.160101.0800):Microsoft Corporation
		UMPDC.dll:User Mode Power Dependency Coordinator:10.0.26100.1301 (WinBuild.160101.0800):Microsoft Corporation
		USER32.dll:Çok Kullanıcılı Windows USER API İstemci DLL'si:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		USERENV.dll:Userenv:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		VCRUNTIME140.dll:Microsoft® C Runtime Library:14.29.30139.0 built by: vcwrkspc:Microsoft Corporation
		VERSION.dll:Version Checking and File Installation Libraries:10.0.26100.1150 (WinBuild.160101.0800):Microsoft Corporation
		WINHTTP.dll:Windows HTTP Hizmetleri:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		WINMM.dll:MCI API DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		WINTRUST.dll:Microsoft Trust Verification APIs:10.0.26100.2894 (WinBuild.160101.0800):Microsoft Corporation
		WS2_32.dll:Windows Socket 2.0 32 Bit DLL'si:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		WSOCK32.dll:Windows Socket 32-Bit DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		amsi.dll:Anti-Malware Scan Interface:10.0.26100.1150 (WinBuild.160101.0800):Microsoft Corporation
		bcrypt.dll:Windows Şifreleme Temel Elemanları Kitaplığı:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		bcryptPrimitives.dll:Windows Cryptographic Primitives Library:10.0.26100.2033 (WinBuild.160101.0800):Microsoft Corporation
		cfgmgr32.dll:Configuration Manager DLL:10.0.26100.2454 (WinBuild.160101.0800):Microsoft Corporation
		clbcatq.dll:COM+ Configuration Catalog:2001.12.10941.16384 (WinBuild.160101.0800):Microsoft Corporation
		combase.dll:Windows için Microsoft COM:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		dbgcore.DLL:Windows Core Debugging Helpers:10.0.26100.2454 (WinBuild.160101.0800):Microsoft Corporation
		dhcpcsvc.DLL:DHCP İstemci Hizmeti:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		dhcpcsvc6.DLL:DHCPv6 İstemcisi:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		dinput8.dll:Microsoft DirectInput:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		directxdatabasehelper.dll:DirectXDatabaseHelper:10.0.26100.2454 (WinBuild.160101.0800):Microsoft Corporation
		dwmapi.dll:Microsoft Masaüstü Pencere Yöneticisi API'si:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		dxcore.dll:DXCore:10.0.26100.2454 (WinBuild.160101.0800):Microsoft Corporation
		dxgi.dll:DirectX Graphics Infrastructure:10.0.26100.2454 (WinBuild.160101.0800):Microsoft Corporation
		fwpuclnt.dll:FWP/IPsec Kullanıcı Modu API'si:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		gdi32full.dll:GDI Client DLL:10.0.26100.2454 (WinBuild.160101.0800):Microsoft Corporation
		glfw.dll:GLFW 3.4.0 DLL:3.4.0:GLFW
		icm32.dll:Microsoft Color Management Module (CMM):10.0.26100.2314 (WinBuild.160101.0800):Microsoft Corporation
		iertutil.dll:Internet Explorer için çalışma zamanı yardımcı yazılımı:11.00.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		igc64.dll:Intel Graphics Shader Compiler for Intel(R) Graphics Accelerator:31.0.101.3887:Intel Corporation
		igdgmm64.dll:User Mode Driver for Intel(R) Graphics Technology:31.0.101.3887:Intel Corporation
		igdml64.dll:Metrics Library for Intel(R) Graphics Technology:31.0.101.3887:Intel Corporation
		igxelpicd64.dll:OpenGL(R) Driver for Intel(R) Graphics Accelerator:31.0.101.3887:Intel Corporation
		inputhost.dll:InputHost:10.0.26100.2454 (WinBuild.160101.0800):Microsoft Corporation
		java.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		javaw.exe:OpenJDK Platform binary:17.0.8.0:Microsoft
		jemalloc.dll
		jimage.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		jli.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		jna4871472067857136352.dll:JNA native library:6.1.4:Java(TM) Native Access (JNA)
		jsvml.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		jvm.dll:OpenJDK 64-Bit server VM:17.0.8.0:Microsoft
		kernel.appcore.dll:AppModel API Host:10.0.26100.1591 (WinBuild.160101.0800):Microsoft Corporation
		lwjgl.dll
		lwjgl_opengl.dll
		lwjgl_stb.dll
		management.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		management_ext.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		mscms.dll:Microsoft Renk Eşleştirme Sistemi DLL'si:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		msvcp140.dll:Microsoft® C Runtime Library:14.29.30139.0 built by: vcwrkspc:Microsoft Corporation
		msvcp_win.dll:Microsoft® C Runtime Library:10.0.26100.1882 (WinBuild.160101.0800):Microsoft Corporation
		msvcrt.dll:Windows NT CRT DLL:7.0.26100.1882 (WinBuild.160101.0800):Microsoft Corporation
		mswsock.dll:Microsoft Windows Sockets 2.0 Servis Sağlayıcı:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		napinsp.dll:E-posta Adlandırma Shim Sağlayıcısı:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		ncrypt.dll:Windows NCrypt Yönlendiricisi:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		net.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		netutils.dll:Net Win32 API Helpers DLL:10.0.26100.1882 (WinBuild.160101.0800):Microsoft Corporation
		nio.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		nlansp_c.dll:NLA Namespace Service Provider DLL:10.0.26100.1150 (WinBuild.160101.0800):Microsoft Corporation
		ntdll.dll:NT Katmanı DLL’si:10.0.26100.2454 (WinBuild.160101.0800):Microsoft Corporation
		opengl32.dll:OpenGL Client DLL:10.0.26100.1882 (WinBuild.160101.0800):Microsoft Corporation
		perfos.dll:Windows Sistem Performans Nesneleri DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		pfclient.dll:SysMain Client:10.0.26100.1301 (WinBuild.160101.0800):Microsoft Corporation
		profapi.dll:User Profile Basic API:10.0.26100.2454 (WinBuild.160101.0800):Microsoft Corporation
		rasadhlp.dll:Remote Access AutoDial Helper:10.0.26100.1150 (WinBuild.160101.0800):Microsoft Corporation
		rsaenh.dll:Microsoft Enhanced Cryptographic Provider:10.0.26100.1 (WinBuild.160101.0800):Microsoft Corporation
		sechost.dll:Host for SCM/SDDL/LSA Lookup APIs:10.0.26100.1 (WinBuild.160101.0800):Microsoft Corporation
		shlwapi.dll:Kabuk Hafif Hizmet Programı Kitaplığı:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		srvcli.dll:Server Service Client DLL:10.0.26100.1150 (WinBuild.160101.0800):Microsoft Corporation
		sunmscapi.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		textinputframework.dll:"TextInputFramework.DYNLINK":10.0.26100.2454 (WinBuild.160101.0800):Microsoft Corporation
		ucrtbase.dll:Microsoft® C Runtime Library:10.0.26100.1882 (WinBuild.160101.0800):Microsoft Corporation
		urlmon.dll:Win32 için OLE32 Uzantıları:11.00.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		uxtheme.dll:Microsoft UxTheme Kitaplığı:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		vcruntime140_1.dll:Microsoft® C Runtime Library:14.29.30139.0 built by: vcwrkspc:Microsoft Corporation
		verify.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		win32u.dll:Win32u:10.0.26100.2605 (WinBuild.160101.0800):Microsoft Corporation
		windows.staterepositorycore.dll:Windows StateRepository API Core:10.0.26100.1882 (WinBuild.160101.0800):Microsoft Corporation
		windows.storage.dll:Microsoft WinRT Depolama API:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		winrnr.dll:LDAP RnR Provider DLL:10.0.26100.1882 (WinBuild.160101.0800):Microsoft Corporation
		wintypes.dll:Windows Temel Türler DLL'si:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		wshbth.dll:Windows Sockets Helper DLL:10.0.26100.1882 (WinBuild.160101.0800):Microsoft Corporation
		xinput1_4.dll:Microsoft Common Controller API:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		zip.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
Stacktrace:
	at net.minecraft.client.main.Main.main(Main.java:169) ~[Cromta's%20Solo%20Leveling%20pack%20Cromta's%20Solo%20Leveling%20Modpack.jar:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$launchService$0(CommonClientLaunchHandler.java:27) ~[fmlloader-1.19.4-45.2.0.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:106) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:77) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.8.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


-- System Details --
Details:
	Minecraft Version: 1.19.4
	Minecraft Version ID: 1.19.4
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 17.0.8, Microsoft
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), Microsoft
	Memory: 218599176 bytes (208 MiB) / 503316480 bytes (480 MiB) up to 11274289152 bytes (10752 MiB)
	CPUs: 20
	Processor Vendor: GenuineIntel
	Processor Name: 12th Gen Intel(R) Core(TM) i7-12700H
	Identifier: Intel64 Family 6 Model 154 Stepping 3
	Microarchitecture: Alder Lake
	Frequency (GHz): 2.69
	Number of physical packages: 1
	Number of physical CPUs: 14
	Number of logical CPUs: 20
	Graphics card #0 name: NVIDIA GeForce RTX 3050 Ti Laptop GPU
	Graphics card #0 vendor: NVIDIA (0x10de)
	Graphics card #0 VRAM (MB): 4095.00
	Graphics card #0 deviceId: 0x25a0
	Graphics card #0 versionInfo: DriverVersion=32.0.15.6614
	Graphics card #1 name: Intel(R) Iris(R) Xe Graphics
	Graphics card #1 vendor: Intel Corporation (0x8086)
	Graphics card #1 VRAM (MB): 1024.00
	Graphics card #1 deviceId: 0x46a6
	Graphics card #1 versionInfo: DriverVersion=31.0.101.3887
	Memory slot #0 capacity (MB): 8192.00
	Memory slot #0 clockSpeed (GHz): 3.20
	Memory slot #0 type: DDR4
	Memory slot #1 capacity (MB): 8192.00
	Memory slot #1 clockSpeed (GHz): 3.20
	Memory slot #1 type: DDR4
	Virtual memory max (MB): 22528.09
	Virtual memory used (MB): 15723.04
	Swap memory total (MB): 6400.00
	Swap memory used (MB): 418.11
	JVM Flags: 9 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xss1M -Xmx10752M -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
	Launched Version: Cromta's Solo Leveling pack Cromta's Solo Leveling Modpack
	Backend library: LWJGL version 3.3.1 build 7
	Backend API: Intel(R) Iris(R) Xe Graphics GL version 3.2.0 - Build 31.0.101.3887, Intel
	Window size: <not initialized>
	GL Caps: Using framebuffer using OpenGL 3.2
	GL debug messages: 
	Using VBOs: Yes
	Is Modded: Definitely; Client brand changed to 'forge'
	Type: Client (map_client.txt)
	CPU: 20x 12th Gen Intel(R) Core(TM) i7-12700H
	ModLauncher: 10.0.8+10.0.8+main.0ef7e830
	ModLauncher launch target: forgeclient
	ModLauncher naming: srg
	ModLauncher services: 
		mixin-0.8.5.jar mixin PLUGINSERVICE 
		eventbus-6.0.3.jar eventbus PLUGINSERVICE 
		fmlloader-1.19.4-45.2.0.jar slf4jfixer PLUGINSERVICE 
		fmlloader-1.19.4-45.2.0.jar object_holder_definalize PLUGINSERVICE 
		fmlloader-1.19.4-45.2.0.jar runtime_enum_extender PLUGINSERVICE 
		fmlloader-1.19.4-45.2.0.jar capability_token_subclass PLUGINSERVICE 
		accesstransformers-8.0.4.jar accesstransformer PLUGINSERVICE 
		fmlloader-1.19.4-45.2.0.jar runtimedistcleaner PLUGINSERVICE 
		modlauncher-10.0.8.jar mixin TRANSFORMATIONSERVICE 
		modlauncher-10.0.8.jar fml TRANSFORMATIONSERVICE 
	FML Language Providers: 
		minecraft@1.0
		lowcodefml@null
		javafml@null
	Mod List: 
		client-1.19.4-20230314.122934-srg.jar             |Minecraft                     |minecraft                     |1.19.4              |NONE      |Manifest: a1:d4:5e:04:4f:d3:d6:e0:7b:37:97:cf:77:b0:de:ad:4a:47:ce:8c:96:49:5f:0a:cf:8c:ae:b2:6d:4b:8a:3f
		forge-1.19.4-45.2.0-universal.jar                 |Forge                         |forge                         |45.2.0              |NONE      |Manifest: 84:ce:76:e8:45:35:e4:0e:63:86:df:47:59:80:0f:67:6c:c1:5f:6e:5f:4d:b3:54:47:1a:9f:7f:ed:5e:f2:90
  
