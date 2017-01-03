<?xml version="1.0" encoding="UTF-8"?>
<settings>
	<software>
		<schueco ADDCOM="1">
			<addins>
				<databases>
					<fatdb CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\User\Local\FabricationTimeCalculation" DONOTREMOVEDSN="1" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PHYSICALNAME="FATDB_G3.mdb" DSNPREFIX="G3_"></fatdb>
					<pbz DSNPREFIX="G3_" CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DONOTREMOVEDSN="1" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PHYSICALNAME="PBZ.mdb"></pbz>
					<pbzuser1 CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\User\Local\MachineControl" DONOTREMOVEDSN="1" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PHYSICALNAME="PBZUser1_G3.mdb" DSNPREFIX="G3_"></pbzuser1>
					<pbzuser2 CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\User\Local\MachineControl" DONOTREMOVEDSN="1" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PHYSICALNAME="PBZUser2_G3.mdb" DSNPREFIX="G3_"></pbzuser2>
				</databases>
				<fat FATPATH="C:\Program Files (x86)\Schueco\Schuecal\bin" IMPORTLOGFILE="C:\ProgramData\Schueco\SchueCal\System\FabricationTimeCalculation\FATImport.txt" TEMPLATEPATH="C:\ProgramData\Schueco\SchueCal\System\FabricationTimeCalculation\Templates\"></fat>
				<pricelist PRICELISTPICTUREPATH="C:\ProgramData\Schueco\SchueCal\User\Local\PricelistGeneration"></pricelist>
			</addins>
			<contacts DIRECTORY="C:\ProgramData\Schueco\SchueCal\User\Local\Contacts"></contacts>
			<schuecal2000 OLDWINTERGARDENSYSTEMS="0" P2D_ACTIVATE="0" SHOWINSERTDOORINFILLCOMMAND="0" USEDIN_EN_12519="1" ALLOWTRACE="0" DISABLEACCELERATIONATI="1" CATALOGRESEARCHDRIVE="Docu Center - Online" CATALOGRESEARCHREADERPATH="" ACTIVATECATALOGRESEARCH="1" DEFAULTLANGUAGE="49" DISPLAYITEMTEXT="1" HOMEDIRECTORY="C:\Program Files (x86)\Schueco\Schuecal" OUTPUTDIRECTORY="C:\ProgramData\Schueco\SchueCal\Output" P2D_FILESTORE="0" PROJECTTYPE="0" SCRIPTDIRECTORY="C:\Program Files (x86)\Schueco\Schuecal\Scripts" TEMPLATEDIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data\Templates" USERSCRIPTDIRECTORY="C:\ProgramData\Schueco\SchueCal\User\Local\UserDefinedOutlineTemplates" USERTFOUTPUT="1" ZIPDIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data\ZipDaten" ELEMENTDIRECTORY="C:\ProgramData\Schueco\SchueCal\User\Local\Element" ENABLEONLINEORDER="" ALLOWFREEDESIGN="" EXPORTFABRICATIONLIST="" GASKETBOX="0" WORKBENCHPATH="C:\ProgramData\Schueco\Schuecal\Workbench_G3.xml" WK2_NL="0" TBMWITHOUTDOORLOCK="0" CALCSURFACEUSA="0" APPLICATIONBUILDNR="4804" HIDECALCDATAMESSAGES="0" ENABLEEXCHANGEARTICLES="0" MIXEDVENDOR="0" HIDEARTICLEWEIGHT="0" SHOWEDVCODE="0" WERKSVERBUND2FARBIG="0" AKSCE="0" VULCFRAMEPRICEDETAIL="0" HIDECLASSICCONFIGS="1" OFFERWITHFITTINGDETAILS="1" CYLINDER_22="0" USERSTATISTICS="1">
				<cprsettings></cprsettings>
				<databases>
					<availableedvcodes CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="AvailableEdvCodes.mdb" USERNAME=""></availableedvcodes>
					<basedata CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\User\Local" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="BaseData_G3.mdb" USERNAME=""></basedata>
					<cadexport CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\User\Local" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="CadExport_G3.mdb" USERNAME=""></cadexport>
					<changelog CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\User\Local" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="ChangeLog_G3.mdb" USERNAME=""></changelog>
					<connector ALLOWCACHING="1" CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="Connector.mdb" USERNAME=""></connector>
					<fat ALLOWCACHING="1" CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="FAT.mdb" USERNAME=""></fat>
					<fittings ALLOWCACHING="1" CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="Fittings.mdb" USERNAME=""></fittings>
					<fittingsjag ALLOWCACHING="1" CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="FittingsJAG.mdb" USERNAME=""></fittingsjag>
					<glazing ALLOWCACHING="1" CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="Glazing.mdb" USERNAME=""></glazing>
					<jointing ALLOWCACHING="1" CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="Jointing.mdb" USERNAME=""></jointing>
					<offermanagement CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\User\Local\Quotation" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PHYSICALNAME="Offermanagement_G3.mdb" PASSWORD="" USERNAME=""></offermanagement>
					<openings ALLOWCACHING="1" CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="Openings.mdb" USERNAME=""></openings>
					<opt CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\User\Local" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="opt_G3.mdb" USERNAME=""></opt>
					<optschueco ALLOWCACHING="0" CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="OptSchueco.mdb" USERNAME=""></optschueco>
					<otherfittings CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\User\Local" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PHYSICALNAME="OtherFittings_G3.mdb"></otherfittings>
					<pricelist.j PHYSICALNAME="PriceListJ044.mdb" ALLOWCACHING="1" CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||"></pricelist.j>
					<pricelist.s ALLOWCACHING="1" CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PHYSICALNAME="PriceList044.mdb"></pricelist.s>
					<profiles ALLOWCACHING="1" CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s|SystemDB=C:\ProgramData\Schueco\SchueCal\System\Data\Profiles.mdw||" PASSWORD="" PHYSICALNAME="Profiles.mdb" USERNAME=""></profiles>
					<pvc ALLOWCACHING="1" CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PHYSICALNAME="PVC.mdb" USERNAME=""></pvc>
					<schuecodata ALLOWCACHING="1" CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="SchuecoData.mdb" USERNAME=""></schuecodata>
					<spannlage CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data\Templates" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PHYSICALNAME="Spannlage.mdb" PASSWORD="" USERNAME=""></spannlage>
					<userdata CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\User\Local" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="UserData_G3.mdb" USERNAME=""></userdata>
					<userprof CONNECTSTRING="Provider=MSDASQL;" DIRECTORY="C:\ProgramData\Schueco\SchueCal\User\Local" DONOTREMOVEDSN="1" DSNPREFIX="G3_" ODBCDRIVER="Microsoft Access Driver (*.mdb)" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" PASSWORD="" PHYSICALNAME="Userprof_G3.mdb" USERNAME=""></userprof>
					<output DIRECTORY="C:\ProgramData\Schueco\SchueCal\System\Data" PHYSICALNAME="Output.mdb" CONNECTSTRING="Provider=Microsoft.Jet.OLEDB.4.0;" ODBCPARAMETER="DSN=%s|DefaultDir=%s|DBQ=%s||" ODBCDRIVER="Microsoft Access Driver (*.mdb)" DSNPREFIX="G3_"></output>
				</databases>
				<epdsettings EMAILCONTACT="epdinfo@schueco.com"></epdsettings>
				<ngc GEE="27"></ngc>
				<erpisprojectsettings REGISTERED="0" USERNAME="" PASSWORD="" TABLE="" DBNAME=""></erpisprojectsettings>
				<logging MODE="1" USE_LOG_INDENTING="1" USE_SYSTIME="1" USE_MSEC="0" LOG_CACHE_FLUSH_INTERVAL_IN_SECS="">
					<modules ALLOW=""></modules>
					<levels ALLOW=""></levels>
				</logging>
			</schuecal2000>
		</schueco>
	</software>
</settings>
