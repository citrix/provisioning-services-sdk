# MapiReturn returnCode and exceptionType

0 Success: The command succeeded.

1 NotImplemented: The \[v1\] feature has not been implemented.

2 InvalidCommand: The \[v1\] command does not exist.

3 InvalidField: The \[v1\] field does not exist.

4 InvalidFieldFormat: The \[v1\] field is not formatted properly, the correct format is \[v2\].

5 InvalidParameter: The \[v1\] parameter is not valid.

6 InvalidParameterFormat: The \[v1\] parameter is not formatted property, the correct format is \[v2\].

7 ReadOnlyField: Unable to change the \[v1\] field because it is read-only.

8 RequiredFieldMissing: The required \[v1\] field is missing.

9 RequiredFieldsMissing: The required \[v1\] or \[v2\] field is missing.

10 RequiredParameterMissing: The required \[v1\] parameter is missing.

11 RequiredParametersMissing: The required \[v1\] or \[v2\] parameter is missing.

12 InternalIdAndNameFieldsMustBeDefined: An internal error occurred. The \[v1\] field is not the next FieldSettings object after the ID.

13 NoFarmAccess: The domain/user does not have access to the Farm.

14 InvalidForeignKeyValue: The \[v1\] field with value \[v2\] is an invalid foreign key.

15 SetupError: The system was not configured correctly.

16 Executing: The \[v1\] command can only be called one at a time. Wait for the command to finish before running again.

17 NoDiskMapped: A vDisk has not yet been mapped.

18 DatabaseError: A database error occurred.

19 DuplicateKey: To avoid creating a duplicate key, the Add or Set command was cancelled.

20 DatabaseErrorMissed: An internal error occurred. An uncaught database error occurred.

21 AddCommandFailed: No objects were added during the last 'Add' command.

22 InsufficientPrivileges: Access denied. The appropriate privileges are not assigned to perform this task.

23 ZeroObjectsAffected: No object was added, updated, or deleted in the last operation.

24 OtherException: An unexpected MAPI error occurred.

25 InvalidFieldLength: The \[v1\] field value is too long, maximum length is \[v2\].

26 InvalidFieldValueMinMax: The \[v1\] field value is invalid, the minimum is \[v2\] and the maximum is \[v3\].

27 InvalidFieldValue: The \[v1\] field can only have values \[v2\] or \[v3\].

28 TooManyParameters: More parameters were specified than permitted.

29 TooFewParameters: Not enough identifying parameters specified.

30 FollowingParametersMissing: To use the \[v1\] parameter, \[v2\] or \[v3\] must also be used.

31 InconsistentData: The action is canceled because the Store directory date/times does not match. Update the Store directories to match.

32 DatabaseOpenFailed: Unable to contact the database server. Ensure Citrix Provisioning server is configured correctly.

33 DatabaseVersionWrong: The wrong database version is being used.  Found version number: \[v1\] Expected version number: \[v2\]

34 DatabaseVersionNotFound: The database version number does not exist or was not found. Ensure Citrix Provisioning server is configured correctly.

35 SomeRequiredParametersMissing: Required parameters are missing.

36 PartialError: The following items failed:

item1 Error message...

item2 Error message...

37 NoItemsToProcess: There are no items to process.

38 NoDefaultCollectionDefined: Unable to add a Device until a default Collection is set.

39 NoDefaultSiteDefined: A default Site is not set, no Devices can be added.

40 InvalidCollection: The specified Collection does not exist.

41 InvalidAuthGroup: The specified AuthGroup does not exist.

42 InvalidGroup: The specified Group does not exist.

43 InvalidDevice: The specified Device does not exist.

44 InvalidDiskLocator: The specified vDisk does not exist.

45 InvalidServer: The specified Server does not exist.

46 InvalidServerSite: Server specified is not in the Site specified.

47 InvalidStoreSite: Store specified is not for the Site specified.

48 InvalidSiteView: The specified Site View does not exist.

49 InvalidSite: The specified Site does not exist.

50 InvalidDeviceDiskLocator: The specified Device or vDisk does not exist.

51 InvalidDeviceImport: Import failed because the file must have Device Name, Mac Address, Site Name, and Collection Name, and they must be tab or comma-delimited.

52 InvalidServerFrom: The Server to copy \[v1\]=\[v2\] was not found.

53 InvalidServerTo: No Server to copy to (\[v1\]=\[v2\]) was found.

54 InvalidDeviceFrom: The Device to copy \[v1\]=\[v2\] was not found.

55 InvalidDeviceTo: No Devices to copy to are found.

56 InvalidDiskFrom: The vDisk to copy \[v1\]=\[v2\] was not found.

57 InvalidDiskTo: No vDisk to copy to (\[v1\]=\[v2\]) was found.

58 InvalidDiskPath: The path '\[v1\]' to the vDisk file is not found.

59 VDiskFileNotFound: \[v1\]: vDisk file was not found.

60 InvalidDiskServer: There is no Server that can serve the vDisk \[v1\] or the Store to which this vDisk belongs. Verify that one or more Servers belonging to the Store are online and that there is sufficient free space for the operation you are attempting.

61 InvalidDiskForServer: Server \[v1\] cannot access all versions of vDisk \[v2\], the vDisk was updated on at least one other Server.

62 SameSiteRequired: Objects within the same Site must be selected.

63 TooFewFields: Not enough fields for a record.

64 ADerrorDC: Unable to connect to the Domain Controller (if any) or the default rootDSE. Error code: \[v1\], message: \[v2\], provider: \[v3\].

65 ADerrorOU: Unable to get the Organizational Unit setting (if any). Error code: \[v1\], message: \[v2\], provider: \[v3\].

66 ADerrorDefaultContainer: Unable to get the default computer accounts container (default location is Active Directory root> Computers). Error code: \[v1\], message: \[v2\], provider: \[v3\].

67 ADerrorCreate: Unable to create the computer account in Active Directory. Ensure the account does not already exist and that the appropriate permissions are available to perform this task. Error code: \[v1\], message: \[v2\], provider: \[v3\].

68 ADerrorNewAccount: Unable to get the newly created Active Directory computer account. Error code: \[v1\], message: \[v2\], provider: \[v3\].

69 ADerrorSam: Unable to set the Active Directory samAccountName property. Ensure the appropriate permissions exist to perform this task. Error code: \[v1\], message: \[v2\], provider: \[v3\].

70 ADerrorUserAccount: Unable to set the Active Directory userAccountControl property. Ensure the appropriate permissions exist to perform this task. Error code: \[v1\], message: \[v2\], provider: \[v3\].

71 ADerrorSave: Unable to save Active Directory change. Ensure the appropriate permissions exist to perform this task. Error code: \[v1\], message: \[v2\], provider: \[v3\].

72 ADerrorSetPassword: Unable to set a new password for this user account. Ensure the appropriate permissions exist to perform this task. Error code: \[v1\], message: \[v2\], provider: \[v3\].

73 ADerrorAddTrustee: Unable to add trustee (if any). Error code: \[v1\], message: \[v2\], provider: \[v3\].

74 ADerrorEnableAccount: Unable to enable the Active Directory account. Error code: \[v1\], message: \[v3\], provider: \[v2\].

75 ADerrorAlreadyExists: The computer name is already in use. Error code: \[v1\], message: \[v3\], provider: \[v2\]. Select a unique name for this machine.

76 ADerrorGeneral: A general Active Directory error occurred. Error code: \[v1\], message: \[v2\], provider: \[v3\].

77 ADerrorDirectorySearch: Unable to find Active Directory items meeting the search criteria entered. Error code: \[v1\], message: \[v2\], provider: \[v3\].

78 ADerrorSearchComputerAccount: Unable to perform the computer accounts search. Error code: \[v1\], message: \[v2\], provider: \[v3\].

79 ADerrorComputerAccountNotFound: Specified computer account not found. Error code: \[v1\], message: \[v2\], provider: \[v3\].

80 ADerrorComputerAccountHold: This computer account is currently unavailable. Ensure that Active Directory is running properly. Error code: \[v1\], message: \[v2\], provider: \[v3\].

81 ADerrorComputerAccountMove: Failed to move the computer account to the target organizational unit set (also returned if caller lacks permission). Error code: \[v1\], message: \[v2\], provider: \[v3\].

82 ADerrorDelete: Unable to delete this computer account. Ensure the appropriate permissions exist to perform this task. Error code: \[v1\], message: \[v2\], provider: \[v3\].

83 ADerrorPasswordGeneration: Unable to generate this password. Ensure the appropriate permissions exist to perform this task.

84 MapDiskNoDriver: Unable to map vDisk because a driver was not found.

85 MapDiskDeniedByServer: Unable to map the vDisk. Mapping was denied by the Server.

86 MapDiskLocalAccessDenied: Unable to map the vDisk. Denied local access.

87 MapDiskMiniportError: Unable to map vDisk because of a Miniport error.

88 UnmapDiskFailed: Failed to unmap a vDisk.

89 DuplicateDisk: The vDisk \[v1\] already exists on \[v2\] at \[v3\].

90 DuplicateDiskLocator: A DiskLocator: \[v1\] already exists on Site: \[v2\].

91 DiskCreationInProgress: The vDisk \[v1\] is being created on \[v2\] at \[v3\].

92 InvalidServerStore: A database integrity error occurred. The Server is not set to deliver vDisks from the Store, but should be.

93 InvalidStore: The specified Store does not exist.

94 InvalidFarmView: Farm View specified does not exist.

95 InvalidStorePath: Store path is empty.

96 ManagementInterfaceError:

Management Interface: Undefined error.

Management Interface: Database interface is inaccessible.

Management Interface: Database interface library is inaccessible.

Management Interface: The database access library is a version incompatible with the Management Server.

Management Interface: Database interface library is invalid.

Management Interface: Database interface could not be created.

Management Interface: Database could not be opened.

Management Interface: Database is in use.

Management Interface: Database error occurred.

Management Interface: Not implemented.

Management Interface: Registry entry was not found.

Management Interface: Request was not created.

Management Interface: Operating System error occurred.

Management Interface: vDisk error.

Management Interface: vDisk header is incomplete.

Management Interface: vDisk footer is incomplete.

Management Interface: vDisk boot record is incomplete.

Management Interface: vDisk boot sector is incomplete.

Management Interface: vDisk size is below the minimum.

Management Interface: vDisk size is above the maximum.

Management Interface: vDisk boot record template is inaccessible.

Management Interface: vDisk boot sector template is inaccessible.

Management Interface: vDisk lock was not found.

Management Interface: vDisk has exclusive lock.

Management Interface: vDisk has shared lock.

Management Interface: vDisk lock error.

Management Interface: vDisk format is incompatible.

Management Interface: vDisk prefooter is incomplete.

Management Interface: vDisk creation is in progress.

Management Interface: vDisk creation information was not found.

Management Interface: vDisk creation cancellation was requested.

Management Interface: vDisk file was not found.

Management Interface: vDisk file path was not found.

Management Interface: vDisk file access was denied.

Management Interface: Cancelled.

Management Interface: Registry key for the product is inaccessible.

Management Interface: Registry key for the installation folder is inaccessible.

Management Interface: Registry key for the management interface is inaccessible.

Management Interface: Registry key for the database path is inaccessible.

Management Interface: Registry key for the management interface IP address is inaccessible.

Management Interface: Buffer size is too small.

Management Interface: Buffer size is too large.

Management Interface: Unknown error.

Management Interface: Remote Server failed to relay a request.

Management Interface: Remote Server is not servicing the Device.

Management Interface: Remote Server or Device refused the request.

Management Interface: Local Server failed to complete a request to a Server or Device.

Management Interface: Local Server failed to complete a request to a Server.

Management Interface: Remote requests were disabled because of an initialization error.

Management Interface: Remote request failed.

Management Interface: Remote request timed out.

Management Interface: Remote request result was not found.

Management Interface: Remote request receiver failed to initialize.

Management Interface: Management command failed for all objects.

Management Interface: Failed to get the preshared key in secure version.

Management Interface: VHD Error.

Management Interface: vDisk properties were lost.

Management Interface: Insufficient Memory.

Management Interface: The network path was not found.

Management Interface: The network name cannot be found.

Management Interface: File already exists.

Management Interface: The geometry of the vDisk is not accessible.

Management Interface: Unable to create the vDisk because the store media is read-only.

Management Interface: vDisk file is being used by another process.

97 ServerTimeout: Server did not respond to a request in time.

98 NotFound: \[v1\] not found.

99 AccountRetrieve: Account information for user \[v1\] was not found.

100 ActiveDevice: The task cannot be performed on active Devices. Shut down the Devices before attempting to perform the task.

101 ActiveDiskLocator: The task cannot be performed on active vDisks. Shut down the Devices that are using the vDisks before attempting to perform the task.

102 AssignedDiskLocator: Unable to delete a vDisk that is currently assigned to a Device. Unassign all Devices, then delete the vDisk.

103 ActiveServer: The task cannot be performed on active Servers. Shut down the Servers before attempting to perform the task.

104 NotEnoughFreeDiskSpace: There is not enough free disk space to create the vDisk.

105 InvalidDiskName: The vDisk name has one or more invalid characters. The invalid characters are < > | " \\ / : \* ?.

106 CannotDeleteLastAuthGroup: Deleting the last Authorization Group causes the system to be inoperable.

107 CannotDeleteUsedAuthGroup: An Authorization Group that is currently in use cannot be deleted.

108 ServerStartFailed: The Server did not start successfully. Ensure the appropriate permissions exist for the service account.

109 ServerStopFailed: The Server did not stop successfully.

110 LockOwnerNotFound: The Device that owns the lock was not found, the vDisk was not unlocked.

111 PossiblySharedVDisk: Unable to delete File \[v1\]. It is possible that the file is being referenced in other Sites or Stores.

112 StorePathInaccessible: The Store path \[v1\] is inaccessible.

113 InvalidAction: The \[v1\] action does not exist.

114 InvalidObjectType: The \[v1\] objectType does not exist.

115 TooManyRecords: The amount of data returned using Get is too large. Use GetFirst and GetNext instead of Get.

116 InvalidUserGroup: The specified UserGroup does not exist.

117 InvalidAuditAction: The specified AuditAction does not exist.

118 LoginFailed: The database login failed. Ensure the appropriate permissions exist to access the database.

119 DatabaseConnectionError: Unable to connect to the database. Restore the connection in order to manage the farm.

120 CreateTriggersParsing: Unable to parse the database script 'CreateTriggers' at: \[v1\]

121 CreateStoredProcParsing: Unable to parse the database script 'CreateStoredProcedures' at: \[v1\]

122 MediaIsReadOnly: Management Interface: Unable to create the vDisk because the store media is read-only.

123 ConnectedDeviceForVirtualHostingPool: Unable to delete this VM from a machine catalog because it is connected to a Delivery Group.

124 ADerrorDN: Unable to get the distinguishedName property. Ensure the appropriate Active Directory permissions exist to perform this task. Error code: \[v1\], message: \[v2\], provider: \[v3\].

125 ADerrorGetSecDes: Unable to get the Active Directory Security Descriptor property. Error code: \[v1\], message: \[v2\], provider: \[v3\].

126 ADerrorSetSecDes: Unable to set the Active Directory Security Descriptor property. Ensure the appropriate permissions exist to perform this task. Error code: \[v1\], message: \[v2\], provider: \[v3\].

127 ADerrorDNSHostName: Unable to set the DNS Host Name property (dNSHostName). Ensure the appropriate permissions exist to perform this task. Error code: \[v1\], message: \[v2\], provider: \[v3\].

128 ADerrorDisplayName: Unable to set the displayName property. Error code: \[v1\], message: \[v2\], provider: \[v3\].

129 ADerrorBind: This device was unable to bind to the Domain Controller. Ensure the Domain Controller is running. Error code: \[v1\], message: \[v2\], provider: \[v3\].

130 ADerrorGetSPN: Unable to get an Active Directory Service Principal Name. Error code: \[v1\], message: \[v2\], provider: \[v3\].

131 ADerrorWriteSPN: Unable to write the Active Directory Service Principal Name. Error code: \[v1\], message: \[v2\], provider: \[v3\]

132 ADerrorSearch: Unable to perform the requested Search. Error code: \[v1\], message: \[v2\], provider: \[v3\].

133 ADerrorMoveToOU: Unable to move the Active Directory account to the requested Organizational Unit. Ensure the appropriate permissions exist to perform this task. Error code: \[v1\], message: \[v2\], provider: \[v3\].

134 ADerrorDeleteAccount: Unable to delete this computer account. Ensure the appropriate permissions exist to delete accounts.  Error code: \[v1\], message: \[v2\], provider: \[v3\].

135 ADerrorBadParameters: Incorrect parameters sent to Citrix Provisioning from  Studio. Error code: \[v1\], message: \[v2\], provider: \[v3\].

136 VolumeInUse: The volume is being used.

137 VolumeAccessDenied: Volume access is denied.

138 VolumeUnknownVolume: An unknown volume was specified.

139 VolumeGeneralError: An error occured when executing a volume command.

140 MaintenanceServerError: Action cannot be performed, \[v1\] is a maintenance server for \[v2\].

141 NotManagedStore: The action cannot be performed because the store is not managed.

142 PathNotExist: The path does not exist on the given Server.

143 PathNoCreatePermission: The path does not have the appropriate create permissions.

144 PathNoReadPermission: The path does not have the appropriate read permissions.

145 PathNoWritePermission: The path does not have the appropriate write permissions.

146 PathNoDeletePermission: The path does not have the appropriate delete permissions.

147 IPCProtocolError: An internal error occurred. A field is missing from the process communication protocol data.

148 InvalidStoreServer: No active Server can serve the Store \[v1\].

149 ConstraintCheck: A database constraint caused an Add or Update to be stopped.

150 VamtNotFound: The Volume Activation Management Tool cannot be found.

151 ADerrorCannotGetObjectSID: Cannot return objectSID. Error code: \[v1\], message: \[v2\], provider: \[v3\].

152 ADerrorCannotDisableAccount: Cannot disable the Active Directory account at this time. Ensure that all account users are logged off before attempting to disable the account. Error code: \[v1\], message: \[v2\], provider: \[v3\].

153 ADerrorFailedToChangePassword: Unable to reset the machine account password. Ensure the appropriate permissions exist to perform this Active Directory task. Error code: \[v1\], message: \[v2\], provider: \[v3\].

154 ADerrorFailedToCopyDCName: Unable to copy the Domain Controller name. Error code: \[v1\], message: \[v2\], provider: \[v3\].

155 ADerrorDCNameIsTooLong: The Domain Controller name entered exceeds the maximum character length of \[v4\]. Error code: \[v1\], message: \[v2\], provider: \[v3\].

156 SiteMakUserPassword: The Site's makUser and makPassword fields must have values.

157 VamtError: See the log for additional error details.

158 InactiveDevice: Device specified is not active.

159 DiskIsInPrivateMode: This task cannot be performed because the vDisk is in private image mode.

160 AlreadyInChangeMode: Unable to complete this operation, vDisk is already in Maintenance, Merge, or Test mode.

161 CannotCreateMaintenanceDisk: Cannot create maintenance vDisk.

162 CannotEnterMaintenanceMode: To place a vDisk in Maintenance Mode requires using a Server. No Server is available at this time.

163 NotInMaintenanceMode: Unable to perform this action because the vDisk is not in Maintenance Mode.

164 NoVersionForMaintenanceMode: Unable to place this vDisk in Maintenance Mode because the highest version is not found.

165 NoVersionFound: Unable to perform this action because a version record was not found in the database.

166 Obsolete: The \[v1\] feature is obsolete.

167 DatabaseWarning: A database warning occurred.

168 DatabaseSQL: A database SQL error occurred.

169 DatabaseResource: A database resource error occurred.

170 InvalidUpdateTask: The specified UpdateTask does not exist.

171 InvalidVirtualHostingPool: The specified VirtualHostingPool does not exist.

172 RemoteCommand: An exception occurred executing a command on a remote Server.

173 IpcNotConfigured: An internal error occurred. The process communication interface must be configured before executing remote commands.

174 DiskAlreadSetForUpdate: The vDisk is already set for Update with Device \[v1\] in Site \[v2\].

175 InvalidDiskVersion: The vDisk Version specified is not valid.

176 HostResolution: Could not resolve the host name for \[v1\].

177 InProcess: The remote task is taking longer than expected. TaskId: \[v1\]

178 DateMustBeInFuture: The \[v1\] must be in the future.

179 InvalidRemoteReturn: The remote command did not return valid data.

180 InvalidParameterValueMinMax: The \[v1\] parameter value is invalid, the minimum is \[v2\] and the maximum is \[v3\].

181 InvalidParameterNotNumeric: The \[v1\] parameter value is invalid, it is not numeric.

182 InvalidParameterNotGuid: The \[v1\] parameter value is invalid, it is not a GUID.

183 PassThroughMessage: \[v1\]

184 DiskUpdateNotEnabled: The Automatic vDisk Update option must be enabled and the vDisk Update Server must be defined. Set these in the Site properties.

185 PvsStatusException:

Windows API error occurred, number 0xE000FFFF.

SQL error occurred, number 0xE001FFFF.

Manager error occurred. Error number 0xE002FFFF.

StreamProcess error occurred. Error number 0xE003FFFF.

Stream Database error occurred. Error number 0xE004FFFF.

Management error occurred. Error number 0xE005FFFF.

Shutdown in progress; request ignored. Error number 0xE0050001.

CreateDiffDisk: Malformed packet; missing one or more arguments. Error number 0xE0050002.

DeleteDiffDisk: Malformed file name; cannot parse directory and name. Error number 0xE0050003.

DeleteDiffDisk: Malformed packet; missing one or more arguments. Error number 0xE0050004.

IPC: Failed to read mtGetLocks parameters. Error number 0xE0050005.

IPC: Failed to read mtGetLockStatus parameters. Error number 0xE0050006.

IPC: Failed to read mtLock parameters. Error number 0xE0050007.

IPC: Failed to read mtUnlock parameters. Error number 0xE0050008.

MergeDisk event: Malformed packet; unknown message type. Error number 0xE0050009.

MergeDisk event: Unknown target request ID. Error number 0xE005000A.

MergeDisk event: Malformed packet; missing one or more arguments. Error number 0xE005000B.

MergeDisk: Malformed packet; missing one or more arguments. Error number 0xE005000C.

ValidateDisk: Malformed packet; missing one or more arguments. Error number 0xE005000D.

VHD Library error occurred. Error number 0xE006FFFF.

VHD Library: Not implemented. Error number 0xE0060001.

VHD Library: Handle pointer is invalid. Error number 0xE0060002.

VHD Library: Length of the path exceeds the limit of the file system. Error number 0xE0060003.

VHD Library: Name is empty. Error number 0xE0060004.

VHD Library: Length of the name exceeds the limit of the file system. Error number 0xE0060005.

VHD Library: Size of a parameter was too big. Error number 0xE0060006.

VHD Library: Size of a parameter was too small. Error number 0xE0060007.

VHD Library: The media is write protected. Error number 0xE0060008.

VHD Library: Type is invalid. Error number 0xE0060009.

VHD Library: Footer is incomplete. Error number 0xE006000A.

VHD Library: Failed to read or write the entire VHD Header. Error number 0xE006000B.

VHD Library: Failed to read or write the entire VHD Block Allocation Table. Error number 0xE006000C.

VHD Library: Failed to read or write all of the VHD properties. Error number 0xE006000D.

VHD Library: VHD footer is corrupt. Error number 0xE006000E.

VHD Library: VHD header is corrupt. Error number 0xE006000F.

VHD Library: Failed to read or write the VHD objects. Error number 0xE0060010.

VHD Library: Destination string is too small. Error number 0xE0060011.

VHD Library: Destination string pointer is NULL. Error number 0xE0060012.

VHD Library: Source string pointer is NULL. Error number 0xE0060013.

VHD Library: Offset is before the beginning of the VHD data area. Error number 0xE0060014.

VHD Library: Offset is after the end of the VHD data area. Error number 0xE0060015.

VHD Library: Failed to allocate memory because it was unavailable. Error number 0xE0060016.

VHD Library: Caller cancelled the last create request. Error number 0xE0060017.

VHD Library: Failed to read or write all of the data as requested. Error number 0xE0060018.

VHD Library: Failed to create a Universal Unique Identification for a VHD. Error number 0xE0060019.

VHD Library: Failed to find the VHD properties. Error number 0xE006001A.

VHD Library: Failed to read or write the entire sector bitmap within a block. Error number 0xE006001B.

VHD Library: Failed to read or write the entire block. Error number 0xE006001C.

VHD Library: Failed to open the file that represents the VHD. Error number 0xE006001D.

VHD Library: Requested number of bytes exceeds the remainder of bytes in a block. Error number 0xE006001E.

VHD Library: Accessed past end of the VHD file. Error number 0xE006001F.

VHD Library: Differencing VHD Unique ID (UUID) differs to parent VHD Unique ID. Error number 0xE0060020.

VHD Library: Differencing VHD timestamp differs to parent VHD last modified time. Error number 0xE0060021.

VHD Library: Failed to read or write the entire VHD Block Allocation Table Map. Error number 0xE0060022.

IPC error occurred. Error number 0xE007FFFF.

There was an unknown transmission error. Error number 0xE0070001.

No response received for successful send. Error number 0xA0070002.

Message processor timed out. Error number 0xE0070003.

Retry limit exhausted. Error number 0xE0070004.

Message recipient task is not active. Error number 0xE0070005.

Socket send/recv cannot be retried. Error number 0xE0070006.

Port shutdown due to connection opens exhausted. Error number 0xE0070007.

Port shutdown due to flood of junk packets. Error number 0xE0070008.

Port shutdown due to receive retries exhausted. Error number 0xE0070009.

Transport does not support fragmentation. Error number 0xE007000A.

One or more packet fragments are missing. Error number 0xE007000B.

Error sending message. Error number 0xE0070100.

Message acknowledgement timeout. Error number 0xA0070101.

Command timeout. Error number 0xE0070102.

Not implemented. Error number 0xE0070103.

Error verifying message port number, must be >= 0 and <= 65535. Error number 0xE0070104.

Command initialization failed. Error number 0xE0070105.

Start of IPC failed. Error number 0xE0070106.

Stop of IPC failed. Error number 0xE0070107.

Memory allocation failure. Error number 0xE0070108.

Internal error, failure to wait long enough for a communication response to be received. Error number 0xE0070109.

Disk Update error occurred. Error number 0xE008FFFF.

Inventory error occurred. Error number 0xE009FFFF.

Inventory Table: Failed to start thread. Error number 0xE0090001.

Inventory Table: Invalid Entry. Error number 0xE0090002.

Inventory Table: Failed to initialize inventory. Error number 0xE0090003.

Shutdown in progress; request ignored. Error number 0xE0090004.

Get Disk Inventory: Parameters bad. Error number 0xE0090033.

Populate database: Failed offline. Error number 0xE0090065.

Populate database: Server get by name failed. Error number 0xE0090066.

Populate database: Uninitialized. Error number 0xE0090067.

Populate database: Get host name failed. Error number 0xE0090068.

Populate database: Char conversion failed. Error number 0xE0090069.

Populate database: Initialization failed. Error number 0xE009006A.

Populate database: Database open failed. Error number 0xE009006B.

Populate database: Get all disk locators failed. Error number 0xE009006C.

Inventory Table: Not yet implemented. Error number 0xE009006D.

Notifier error occurred. Error number 0xE00AFFFF.

MAPI error occurred. Error number 0xE00BFFFF.

186 TaskCancelled: Task \[v1\] is cancelled and is not running.

187 TaskCompleted: Task \[v1\] has been completed and is not running.

188 TaskInProgress: Task \[v1\] is running and cannot be processed.

189 InvalidTask: The specified Task does not exist.

190 InventoryServerCannotContactDatabase: The Inventory Service cannot contact the database.

191 ServerOffline: The Server is offline.

192 ServerStateUnknown: The Server state is unknown.

193 HighestVersionIsPending: Could not complete this action because the  highest vDisk version is still pending. The scheduled date for the version has not occurred yet.

194 MergeInvalidWithCurrentVersions: Merge is not valid with the current versions that exist.

195 DiskInventoryError: vDisk versions are not up to date on all Servers that access this vDisk. Update all Servers with the latest versions of the vDisk files.

196 VDiskFileNotFoundWarning: \[v1\]: vDisk file was not found because it was deleted.

197 CannotAssignActiveServer: Stop the Server before attempting to assign the Server to a different site.

198 CannotAssignServerWithActiveDevice: Before attempting to assign the Server to a different site, shut down Devices connecting to the Server, then shut down the Server.

199 MappedDiskLocator: The vDisk is mapped and cannot be changed.

200 InvalidTemplateDevice: The Template Device must be a Production Device that does not have a Personal vDisk.

201 DeviceWithPersonalVDiskInvalid: Unable to process a Device that uses a personal vDisk.

202 CreatingDisk: Server is creating a vDisk so change cannot be done.

203 AssignedDiskLocatorToDeviceWithPersonalvDisk: Unable to delete a vDisk if the vDisk is currently assigned to a Device that uses a Personal vDisk. Unassign the Device, then delete the vDisk.

204 InvalidMacAddress: The MAC address for this VM is invalid. Configure the VM with a valid MAC address.

205 CannotGetMacFromHypervisor: The hypervisor did not return the MAC address for this VM: \[v1\]

206 Win32SystemException: A system error occurred.

207 RemoteManagementIpCannotBeResolved: Unable to resolve the management IP for Server \[v1\].

208 LocalManagementIpNotSet: The management IP for local server \[v1\] is not set in registry IPC\\IPv4Address.

209 PerformVolumeMaintenanceTaskPermissions: Ensure the Service Account user has the appropriate 'Perform volume maintenance task' permissions.

210 CannotLoginToVirtualHostingPool: Unable to log on to the virtual hosting pool \[v1\]. Ensure that the hypervisior server is running properly.

211 VirtualHostingPoolNotSetForDevice: The virtualHostingPoolId for device \[v1\] with bdmBoot must be set.

212 ActiveBdmBootDeviceCannotProcess: The Boot Device Manager \[v1\] did not process successfully.

213 CannotMovePvdDeviceToAnotherSite: Personal vDisk Devices cannot be moved to another site.

214 XenDesktopSiteInvalid: Citrix Virtual Desktops Site for Devices is not valid, the Citrix Virtual Desktops Site is: \[v1\]

215 XenDesktopServiceListOutOfDate: Citrix Virtual Desktops Site \[v1\] is not reachable, check that the Citrix PVS Soap Server service user has Citrix Virtual Desktops permissions and network connectivity.

216 NoXenDesktopServiceForPersonalVDiskCapability: No Citrix Virtual Desktops service found for Personal vDisk capability.

217 InsufficientPermissionsToPreparePersonalVDisks: The user account for the Citrix PVS Soap Server has insufficient permissions to prepare Personal vDisks.

218 NotEnoughFreeDiskSpaceForManifest: There is not enough free disk space to create the manifest.

219 OperationCannotBeDoneOnlyPvdDevicesAssigned: Operation cannot be done, only Personal vDisk Devices are assigned.

220 DiskFormatCannotBeSetToVHD: The format cannot be set to VHD since no VHD vDisk file is found in the path, \[v1\], for Server, \[v2\].

221 DiskFormatCannotBeSetToVHDX: The format cannot be set to VHDX since no VHDX vDisk file is found in the path, \[v1\], for Server, \[v2\].

222 TemporaryVersionIsSet: This task cannot be performed because a temporary version is set.

223 DiskIsUsingPersistentCacheOnServer: A temporary version cannot be used for a vDisk that is using persistent cache on server.

224 UploadAlreadyInProgress: An upload is already in progress by Server \[v1\].

225 FieldMustBeNull: Field \[v1\] must be null.

226 DuplicateData: Record already exists in \[v1\] table for Farm.

227 CisUploadTokenGenerateError: Error generating upload token for My Citrix username \[v1\] (\[v2\]).

228 InvalidCredentials: The username or password is incorrect.

229 NoWriteAccessToFolders: No write access to folders \[v1\] or \[v2\].

230 ReportCreationError: Error creating problem report: \[v1\].

231 PvsProxyNotSupported: PVS Proxy not supported on this host

232 CannotCreateRegKey: Cannot create Registry key \[v1\]

4100 ADerrorUnexpectedError: An unexpected Active Directory related error occured. Ensure the appropriate permissions exist to perform this task. Error code: \[v1\], message: \[v2\], provider: \[v3\].

## ExecuteAdd

MapiReturn ExecuteAdd(string command,

List<KeyValuePair<string, string>> record,

out string resultId);

### ExecuteAdd AuthGroup

Add an Active Directory or Windows Group for authorization.

record                      Record to add. All record fields that do not have a Default are required.

authGroupName             Name of the Active Directory or Windows Group. Max Length=450

description               User description. Default="" Max Length=250

resultId                    If successful, the GUID of the record added.

### ExecuteAdd CeipData

Add a new entry to CeipData table.

record                      Record to add. All record fields that do not have a Default are required.

enabled                   1 if CEIP is enabled, otherwise 0. Min=0, Max=1

nextUpload                Date and time next CEIP upload is due if enabled is 1. Default=null

inProgress                1 if an upload is currently in progress, otherwise 0. Default=0

serverId                  ID of server that is currently uploading, null if inProgress is 0. Default=null Length=36

oneTimeUpload             1 to perform a one time upload. Default=0

resultId                    If successful, the GUID of the record added.

### ExecuteAdd CisData

Add a new entry to CisData table.

record                      Record to add. All record fields that do not have a Default are required.

userName                  Username used to obtain the token Default=null Max Length=255

path                      Path where the last problem report bundle was saved Default=null Max Length=255

password                  Password of the user required to obtain the token. This is required only by Set and Add

resultId                    If successful, the GUID of the record added.

### ExecuteAdd Collection

Add a Collection to a Site.

record                      Record to add. All record fields that do not have a Default are required.

collectionName            Name of the Collection. It is unique within the Site. Max Length=50

siteId                    GUID of the Site that this Collection is a member of. It is not used with siteName. Length=36

siteName                  Name of the Site that this Collection is a member of. It is not used with siteId.

description               User description. Default="" Max Length=250

lastAutoAddDeviceNumber   The Device Number of the last Auto Added Device. Default=0

enabled                   1 when Devices in the Collection can be booted, 0 otherwise. Default=1

autoAddPrefix             The string put before the Device Number for Auto Add. Default=null ASCII computer name characters no end digit Max Length=12

autoAddSuffix             The string put after the Device Number for Auto Add. Default=null ASCII computer name characters no begin digit Max Length=12

autoAddZeroFill           1 when zeros be placed before the Device Number up to the autoAddNumberLength for Auto Add, 0 otherwise. Default=1

autoAddNumberLength       The maximum length of the Device Number for Auto Add. This length plus the autoAddPrefix length plus the autoAddSuffix length must be less than 16. Required that ((lenautoAddPrefix+lenautoAddSuffix)+autoAddNumberLength)<=15. Min=3, Max=9, Default=4

resultId                    If successful, the GUID of the record added.

### ExecuteAdd Device

Add a new Device to a collection.

record                      Record to add. All record fields that do not have a Default are required.

deviceName                Computer name with no spaces. ASCII computer name characters Max Length=15

collectionId              GUID of the Collection this Device is to be a member of. It is not used with collectionName. Length=36

collectionName            Name of the Collection this Device is to be a member of. siteName or siteId must also be used.

siteId                    GUID of the Site the collectionName is to be a member of. This or siteName is used with collectionName.

siteName                  Name of the Site the collectionName is to be a member of. This or siteId is used with collectionName.

description               User description. Default="" Max Length=250

deviceMac                 Ethernet address as a string in the form XX-XX-XX-XX-XX-XX. Uniquely identifies the Device. Length=17

bootFrom                  Device to boot from. Choices are 1 for vDisk, 2 for Hard Disk, and 3 for Floppy. This cannot be Set for a Device with Personal vDisk. Min=1, Max=3, Default=1

className                 Used by Automatic Update feature to match new versions of Disks to a Device. This cannot be Set for a Device with Personal vDisk. Default="" Max Length=41

port                      UDP port to use with Stream Service. Min=1025, Max=65534, Default=6901

enabled                   1 when it can be booted, 0 otherwise. This cannot be Set for a Device with Personal vDisk. Default=1

localDiskEnabled          If there is a local disk menu choice for the Device, this is 1. This cannot be Set for a Device with Personal vDisk. Default=0

authentication            Device log in authentication. Choices are 0 for none, 1 for User Name/Password, and 2 for Extern. This cannot be Set for a Device with Personal vDisk. Min=0, Max=2, Default=0

user                      Name of user to authenticate before the boot process continues. This cannot be Set for a Device with Personal vDisk. Default="" ASCII Max Length=20

password                  Password of user to authenticate before the boot process continues. This cannot be Set for a Device with Personal vDisk. Default="" ASCII Max Length=100

copyTemplate              1 if the Template Device for the collection, if it exists, should be used for the property settings of the added Device. Default=0

adTimestamp               The time the Active Directory machine account password was generated. Do not set this field, it is only set internally by PVS. Default=0

adSignature               The signature of the Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default=0

adPassword                The Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default="" ASCII Max Length=256

logLevel                  Level to perform logging at. Values are: 0 (None), 1 (Fatal), 2 (Error), 3 (Warning), 4 (Info), 5 (Debug), and 6 (Trace). Min=0, Max=6, Default=0

domainName                Fully qualified name of the domain that the Device belongs to. Do not set this field, it is only set internally by PVS. Default=null Max Length=255

domainObjectSID           The value of the objectSID AD attribute of the same name for the Device's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=186

domainControllerName      The name of the DC used to create the host's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=4000

domainTimeCreated         The time that the computer account was created. Do not set this field, it is only set internally by PVS. Format is: YYYY-MM-DD HH:MM:SS.SSS Default=null

type                      1 when it performs test of Disks, 2 when it performs maintenance on Disks, 3 when it has a Personal vDisk, 4 when it has a Personal vDisk and performs tests, 0 otherwise. Min=0, Max=2, Default=0

localWriteCacheDiskSize   The size in GB to format the Device cache file disk. If the value is 0, then the disk is not formatted. Min=0, Max=2048, Default=0

virtualHostingPoolId      GUID that uniquely identifies the Virtual Hosting Pool for a VM. This is needed when Adding a VM device. Default=null Length=36

hypVmId                   Hypervisor VM ID for HCL Default=null Max Length=250

bdmBoot                   Use PXE boot when set to 0, BDM boot when set to 1. Default is PXE Default=0

bdmType                   Use PXE boot when set to 0, BDM (Bios) boot when set to 1 and BDM (Uefi) boot when set to 2.  Default=0

bdmFormat                 1 use VHD for BDMboot, 2 use ISO, 3 use USB. Default=0

bdmUpdated                Timestamp of the last BDM boot disk update. Default=null

bdmCreated                Timstamp when BDM device was created  Default=null

xsPvsProxyUuid            UUID of XenServer PVS\_proxy Default=null Length=36

enableXsProxy             Enable XenServerProxy when set to 1 Default=null

resultId                    If successful, the GUID of the record added.

### ExecuteAdd DeviceWithPersonalvDisk

Add a new Device with Personal vDisk to a collection.

record                      Record to add. All record fields that do not have a Default are required.

deviceName                Computer name with no spaces. ASCII computer name characters Max Length=15

collectionId              GUID of the Collection this Device with Personal vDisk is to be a member of. It is not used with collectionName. Length=36

collectionName            Name of the Collection this Device with Personal vDisk is to be a member of. siteName or siteId must also be used.

diskLocatorId             GUID of the Disk Locator to update with this Device.

siteId                    GUID of the Site the collectionName is to be a member of. This or siteName is used with collectionName.

siteName                  Name of the Site the collectionName is to be a member of. This or siteId is used with collectionName.

description               User description. Default="" Max Length=250

deviceMac                 Ethernet address as a string in the form XX-XX-XX-XX-XX-XX. Uniquely identifies the Device with Personal vDisk. Length=17

port                      UDP port to use with Stream Service. Min=1025, Max=65534, Default=6901

adTimestamp               The time the Active Directory machine account password was generated. Do not set this field, it is only set internally by PVS. Default=0

adSignature               The signature of the Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default=0

logLevel                  Level to perform logging at. Values are: 0 (None), 1 (Fatal), 2 (Error), 3 (Warning), 4 (Info), 5 (Debug), and 6 (Trace). Min=0, Max=6, Default=0

domainName                Fully qualified name of the domain that the Device with Personal vDisk belongs to. Do not set this field, it is only set internally by PVS. Default=null Max Length=255

domainObjectSID           The value of the objectSID AD attribute of the same name for the Device with Personal vDisk's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=186

domainControllerName      The name of the DC used to create the host's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=4000

domainTimeCreated         The time that the computer account was created. Do not set this field, it is only set internally by PVS. Format is: YYYY-MM-DD HH:MM:SS.SSS Default=null

type                      3 when it has a Personal vDisk, 4 when it has a Personal vDisk and performs tests. Min=3, Max=4, Default=3

pvdDriveLetter            Personal vDisk Drive letter. Range is F to Z. Default=null Max Length=1

localWriteCacheDiskSize   The size in GB to format the Device cache file disk. If the value is 0, then the disk is not formatted. Min=0, Max=2048, Default=0

bdmBoot                   Use BDM instead of PXE boot when set to 1. Default=0

xdSiteId                  GUID of the XenDesktop Site. Default=null Length=36

xdCatalogId               Integer identifier of the XenDesktop Catalog. Default=null

virtualHostingPoolId      GUID that uniquely identifies the Virtual Hosting Pool for a VM. This is needed when Adding a VM device. Default=null Length=36

enableXsProxy             Enable XenServerProxy when set to 1 Default=null

resultId                    If successful, the GUID of the record added.

### ExecuteAdd DiskLocator

Add a Disk Locator to a Site. The Disk file must already exist.

record                      Record to add. All record fields that do not have a Default are required.

diskLocatorName           Name of the Disk Locator File. It is unique within the Store. ASCII Max Length=52

siteId                    GUID of the Site this DiskLocator is to be a member of. It is not used with siteName. Length=36

siteName                  Name of the Site this DiskLocator is to be a member of. It is not used with siteId.

storeId                   GUID of the Store that this Disk Locator is a member of. siteName or siteId must also be used. It is not used with storeName. Length=36

storeName                 Name of the Store that this Disk Locator is a member of. siteName or siteId must also be used. It is not used with storeId.

description               User description. Default="" Max Length=250

menuText                  Text that is displayed in the Boot Menu. If this field has no value, the name value is used. Default="" ASCII Max Length=64

serverId                  GUID of the single Server that this Disk Locator is assigned to. It is not used with serverName. Default=null Length=36

serverName                Name of the single Server that this Disk Locator is assigned to. It is not used with serverId. Default=null

enabled                   1 when this disk can be booted, 0 otherwise. Default=1

rebalanceEnabled          1 when this Server can automatically rebalance Devices, 0 otherwise. Default=0

rebalanceTriggerPercent   Percent over fair load that triggers a dynamic Device rebalance. Min=5, Max=5000, Default=25

subnetAffinity            Qualifier for subnet affinity when assigning a Server. 0=None, 1=Best Effort, 2=Fixed. Min=0, Max=2, Default=0

newDiskWriteCacheType     The writeCacheType that if a new Disk will be created, it will be set with. It is only used when a new Disk is being created. Value are: 0 (Private), (other values are standard image) 1 (Cache on Server), 3 (Cache in Device RAM), 4 (Cache on Device Hard Disk), 7 (Cache on Server, Persistent), or 9 (Cache in Device RAM with Overflow on Hard Disk) Default=0

format                    Format of the image when adding a DiskLocator for a vDisk that has never been added to the Farm. VHDX is the only format that requires this field. Values are: 0 (VHD) and 1 (VHDX). Default=0

resultId                    If successful, the GUID of the record added.

### ExecuteAdd DiskUpdateDevice

Add a new Device related to a Disk that can be updated.

record                      Record to add. All record fields that do not have a Default are required.

deviceName                Computer name with no spaces. ASCII computer name characters Max Length=15

virtualHostingPoolId      GUID of the Virtual Hosting Pool. It is not used with virtualHostingPoolName. Default=null Length=36

virtualHostingPoolName    Name of the Virtual Hosting Pool.

diskLocatorId             GUID of the Disk Locator to update with this Device.

description               User description. Default="" Max Length=250

deviceMac                 Ethernet address as a string in the form XX-XX-XX-XX-XX-XX. Uniquely identifies the Device. Length=17

port                      UDP port to use with Stream Service. Min=1025, Max=65534, Default=6901

adTimestamp               The time the Active Directory machine account password was generated. Do not set this field, it is only set internally by PVS. Default=0

adSignature               The signature of the Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default=0

logLevel                  Level to perform logging at. Values are: 0 (None), 1 (Fatal), 2 (Error), 3 (Warning), 4 (Info), 5 (Debug), and 6 (Trace). Min=0, Max=6, Default=0

domainName                Fully qualified name of the domain that the Device belongs to. Do not set this field, it is only set internally by PVS. Default=null Max Length=255

domainObjectSID           The value of the objectSID AD attribute of the same name for the Device's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=186

domainControllerName      The name of the DC used to create the host's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=4000

domainTimeCreated         The time that the computer account was created. Do not set this field, it is only set internally by PVS. Format is: YYYY-MM-DD HH:MM:SS.SSS Default=null

adPassword                The Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default="" Max Length=256

resultId                    If successful, the GUID of the record added.

### ExecuteAdd FarmView

Add a View to a Farm.

record                      Record to add. All record fields that do not have a Default are required.

farmViewName              name of the Farm View. Max Length=50

description               User description. Default="" Max Length=250

resultId                    If successful, the GUID of the record added.

### ExecuteAdd Server

Add a Server to a Site.

record                      Record to add. All record fields that do not have a Default are required.

serverName                Computer name with no spaces. ASCII computer name characters Max Length=21

siteId                    GUID of the Site this Server is to be a member of. It is not used with siteName. Length=36

siteName                  Name of the Site this Server is to be a member of. It is not used with siteId.

description               User description. Default="" Max Length=250

adMaxPasswordAge          Number of days before a password expires. Min=1, Max=30, Default=7

licenseTimeout            Amount of seconds before a license times out. Min=15, Max=300, Default=30

vDiskCreatePacing         VDisk create time pacing in milliseconds. Min=0, Max=5, Default=0

firstPort                 Number of the first UDP port for use by the Stream Service, First and Last must allow at least 5 ports. Min=1025, Max=65534, Default=6910

lastPort                  Number of the last UDP port for use by the Stream Service, First and Last must allow at least 5 ports. Min=1025, Max=65534, Default=6930

threadsPerPort            Number of worker threads per IO port. Required that (threadPerPort \* numberPorts \* numberIPs) <= 1000. Min=1, Max=60, Default=8

buffersPerThread          Number of buffers per worker thread. Min=1, Max=128, Default=24

serverCacheTimeout        Number of seconds to wait before considering another Server is down. Min=5, Max=60, Default=8

ioBurstSize               Number of bytes read/writes can send in a burst of packets. Required that ioBurstSize/(maxTransmissionUnits-76)<=32. Min=4096, Max=61440, Default=32768

maxTransmissionUnits      Ethernet maximum transmission unit size for the protocol for use for Server and Device. Required that ioBurstSize/(maxTransmissionUnits-76)<=32. Min=502, Max=16426, Default=1506

maxBootDevicesAllowed     Maximum number of Devices allowed to boot simultaneously. Min=1, Max=1000, Default=500

maxBootSeconds            Maximum number of seconds for a Device to boot. Min=10, Max=900, Default=60

bootPauseSeconds          Number of seconds that a Device will pause during login if its server busy. Min=1, Max=60, Default=10

adMaxPasswordAgeEnabled   Age the password, when set to 1. Default=0

eventLoggingEnabled       Enable event logging, when set to 1. Default=0

nonBlockingIoEnabled      Use non-Blocking IO, when set to 1. Default=1

ip                        One or more streaming ip addresses. If more than one ip is included, the ip addresses are comma delimited.

initialQueryConnectionPoolSize  Initial size of database connection pool for non-transactional queries. Min=1, Max=1000, Default=50

initialTransactionConnectionPoolSize  Initial size of database connection pool for transactional queries. Min=1, Max=1000, Default=50

maxQueryConnectionPoolSize  Maximum size of database connection pool for non-transactional queries. Min=1, Max=32767, Default=1000

maxTransactionConnectionPoolSize  Maximum size of database connection pool for transactional queries. Min=1, Max=32767, Default=1000

refreshInterval           Interval, in number of seconds, the server should wait before refreshing settings. If set to 0, unused database connections are never released. Min=0, Max=32767, Default=300

unusedDbConnectionTimeout  Interval, in number of seconds, a connection should go unused before it is to be released. Min=0, Max=32767, Default=300

busyDbConnectionRetryCount  Number of times a failed database connection will be retried. Min=0, Max=32767, Default=2

busyDbConnectionRetryInterval  Interval, in number of milliseconds, the server should wait before retrying to connect to a database. Min=0, Max=10000, Default=25

localConcurrentIoLimit    Maximum concurrent IO transactions it performs for vDisks that are local. A value of 0 disables the feature. Min=0, Max=128, Default=4

remoteConcurrentIoLimit   Maximum concurrent IO transactions it performs for vDisks that are remote. A value of 0 disables the feature. Min=0, Max=128, Default=4

logLevel                  Level to perform logging at. Values are: 0 (None), 1 (Fatal), 2 (Error), 3 (Warning), 4 (Info), 5 (Debug), and 6 (Trace). Min=0, Max=6, Default=4

logFileSizeMax            Maximum size log files can reach in Megabytes. Min=1, Max=50, Default=5

logFileBackupCopiesMax    Maximum number of log file backups. Min=1, Max=50, Default=4

powerRating               A strictly relative rating of this Server's capabilities when compared to other Servers in the Store(s) it belongs too; can be used to help tune load balancing. Min=0.1, Max=1000, Default=1

lastCeipUploadAttempt     Time that this server last attempted a CEIP upload. Default=null

lastBugReportAttempt      Time that this server last attempted to upload or generate a bug report bundle. Default=null

lastBugReportStatus       Status of the last bug report on this server. Default=null Max Length=250

lastBugReportResult       Status of the last bug report on this server. Default=null Max Length=4000

lastBugReportSummary      Summary of the last bug report on this server. Default=null Max Length=250

resultId                    If successful, the GUID of the record added.

### ExecuteAdd Site

Add a Site to the system.

record                      Record to add. All record fields that do not have a Default are required.

siteName                  Name of the Site. Max Length=50

description               User description. Default="" Max Length=250

inventoryFilePollingInterval  The number of seconds between polls for Disk changes in the Stores. Min=1, Max=600, Default=60

enableDiskUpdate          1 when Disk Updated is enabled for the Site, 0 otherwise. Default=0

diskUpdateServerId        GUID of the Disk Update Server for the Site. Not used with diskUpdateServerName. Default=null Length=36

diskUpdateServerName      Name of the Disk Update Server for the Site. Not used with diskUpdateServerId. Default=null

makUser                   User name used for MAK activation. Default=null Max Length=64

makPassword               User password used for MAK activation. Default=null Max Length=64

enableXsProxy             Enable XenServerProxy when set to 1 Default=null

virtualHostingPoolId      GUID of the VirtualHostingPool object.

virtualHostingPoolName    Name of the VirtualHostingPool object.

xsPvsSiteUuid             GUID of the XenServer PVS Site.

resultId                    If successful, the GUID of the record added.

### ExecuteAdd SiteView

Add a View to a Site.

record                      Record to add. All record fields that do not have a Default are required.

siteViewName              Name of the Site View. Max Length=50

siteId                    GUID of the Site this View is to be a member of. It is not used with siteName. Length=36

siteName                  Name of the Site this View is to be a member of. It is not used with siteId.

description               User description. Default="" Max Length=250

resultId                    If successful, the GUID of the record added.

### ExecuteAdd Store

Add a Store to the system.

record                      Record to add. All record fields that do not have a Default are required.

storeName                 Name of the Store. Max Length=50

siteId                    GUID of the Site where Administrators of that Site can change this Store. Not used for Farm Stores. siteName can be used instead. Default=null Length=36

siteName                  Name of the Site where Administrators of that Site can change this Store. Not used for Farm Stores. siteId can be used instead. Default=null

description               User description. Default="" Max Length=250

path                      Default directory path that the Servers use to access this Store. Max Length=255

cachePath                 Default Cache path(s) that the Servers use with this Store. It is an ordered comma-delimited list. If none are specified the caches will be placed in the WriteCache subdirectory of the Store path. Default=None

resultId                    If successful, the GUID of the record added.

### ExecuteAdd UpdateTask

Add a new Update Task for the Site.

record                      Record to add. All record fields that do not have a Default are required.

updateTaskName            Name of the Update Task. It is unique within the Site. Max Length=50

siteId                    GUID of the Site that this Update Task is a member of. It is not used with siteName. Length=36

siteName                  Name of the Site that this Update Task is a member of. It is not used with siteId.

description               User description. Default="" Max Length=250

enabled                   1 when it will be processed, 0 otherwise. Default=1

hour                      The hour of the day to perform the task. Min=0, Max=23, Default=0

minute                    The minute of the hour to perform the task. Min=0, Max=59, Default=0

recurrence                The update will reoccur on this schedule. 0 = None, 1 = Daily, 2 = Every Weekday, 3 = Weekly, 4 = Monthly Date, 5 = Monthly Type. Min=0, Max=5, Default=0

dayMask                   Days selected values. 1 = Monday, 2 = Tuesday, 4 = Wednesday, 8 = Thursday, 16 = Friday, 32 = Saturday, 64 = Sunday, 128 = Day. Default=0. This is used with Weekly and Monthly Type recurrence. Min=1, Max=255, Default=4

date                      Comma delimited days of the month. Numbers from 1-31 are the only valid values. This is used with Monthly Date recurrence. Default="" Max Length=83

monthlyOffset             When to happen monthly. 0 = None, 1 = First, 2 = Second, 3 = Third, 4 = Forth, 5 = Last. This is used with Monthly Type recurrence. Min=0, Max=5, Default=3

esdType                   Esd to use. Valid values are SCCM or WSUS. If no value, a custom script is run on the client. Default=null Max Length=50

preUpdateScript           Script file to run before the update starts. Default=null Max Length=255

preVmScript               Script file to run before the VM is loaded. Default=null Max Length=255

postUpdateScript          Script file to run after the update finishes. Default=null Max Length=255

postVmScript              Script file to run after the VM is unloaded. Default=null Max Length=255

domain                    Domain to add the Disk Update Device(s) to. If not included, the first Domain Controller found on the Server is used. Default=null Max Length=255

organizationUnit          Organizational Unit to add the Disk Update Device(s) to. This parameter is optional. If it is not specified, the device is added to the built in Computers container. Child OU's should be delimited with forward slashes, e.g. "ParentOU/ChildOU". Special characters in an OU name, such as '"', '#', '+', ',', ';', '>', '=', must be escaped with a backslash. For example, an OU called "commaIn,TheMiddle" must be specified as "commaIn\\,TheMiddle". The old syntax of delimiting child OU's with a comma is still supported, but deprecated. Note that in this case, the child OU comes first, e.g. "ChildOU,ParentOU". Default=null Max Length=255

postUpdateApprove         Access to place the version in after the update has occurred. 0 = Production, 1 = Test, 2 = Maintenance. Min=0, Max=2, Default=0

resultId                    If successful, the GUID of the record added.

### ExecuteAdd VirtualHostingPool

Add a new Virtual Hosting Pool for the Site.

record                      Record to add. All record fields that do not have a Default are required.

virtualHostingPoolName    Name of the Virtual Hosting Pool. It is unique within the Site. Max Length=50

siteId                    GUID of the Site that this Virtual Hosting Pool is a member of. It is not used with siteName. Length=36

siteName                  Name of the Site that this Virtual Hosting Pool is a member of. It is not used with siteId.

type                      Type of the Virtual Hosting Pool. 0 = Citrix XenServer, 1 = Microsoft SCVMM/Hyper-V, 2 = VMWare vSphere/ESX. Min=0, Max=3, Default=0

description               User description. Default="" Max Length=250

server                    Name or IP of the Host Server. Max Length=255

port                      Port of the Host Server. Min=80, Max=65534, Default=80

datacenter                Datacenter of the Virtual Hosting Pool. Default="" Max Length=250

updateLimit               Number of updates at the same time. Min=2, Max=1000, Default=1000

updateTimeout             Timeout for updates. Min=2, Max=240, Default=60

shutdownTimeout           Timeout for shutdown. Min=2, Max=30, Default=10

userName                  Name to use when logging into the Server.

password                  Password to use when logging into the Server.

xdHostingUnitUuid         UUID of XenDesktop Hosting Unit Default=null Length=36

prepopulateEnabled        Enable prepopulate when set to 1 Default=0

xsPvsSiteUuid             UUID of XenServer PVS\_site  Default=null Length=36

platformVersion            Hypervisor Host Version  Default=null Max Length=250

xdHcHypervisorConnectionName  Hypervisor Connection Name for HCL Connection Details object Default=null Max Length=250

xdHcHypervisorConnectionUid  Hypervisor Connection Uid for HCL Connection Details object Default=null Max Length=250

xdHcRevision              Revision for HCL Connection Details object Default=null Max Length=250

xdHcCustomProperties      Custom Properties for HCL Connection Details object Default=null Max Length=250

xdHcSslThumbprints        Ssl Thumbprints for HCL Connection Details object Default=null Max Length=250

disableHostXsProxy        True to disable PVS-Accelerator Default=null

resultId                    If successful, the GUID of the record added.

### ExecuteAdd VirtualHostingPoolServer

Add a new Virtual Hosting Pool Server for XenServer PVS proxy

record                      Record to add. All record fields that do not have a Default are required.

virtualHostingPoolId      GUID of the Virtual Hosting Pool being used for XenServer PVS proxy. Length=36

serverId                  GUID of the Server that has a PVS\_server in XenServer Length=36

xsPvsServerUuid           UUID of the XenServer PVS\_server Length=36

resultId                    If successful, the GUID of the record added.

## ExecuteDelete

MapiReturn ExecuteDelete(string command,

List<KeyValuePair<string, string>> parameters);

### ExecuteDelete AuthGroup

Delete an AuthGroup Active Directory or Windows Group name.

parameters                  Parameters needed for this Delete.

One of these required

authGroupId               GUID of the AuthGroup to Delete.

authGroupName             Name of the AuthGroup to Delete.

Optional

force                     When set to 1, the AuthGroup will be Deleted even if being used, otherwise an error is returned if being used.

### ExecuteDelete Collection

Delete a Collection.

parameters                  Parameters needed for this Delete.

This required

collectionId              GUID of the Collection to Delete.

or this required & resolution

collectionName            Name of the Collection to Delete.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteDelete Device

Delete one or more Devices.

parameters                  Parameters needed for this Delete.

One of these required

deviceId                  GUID of the Device to Delete.

deviceName                Name of the Device to Delete.

deviceMac                 MAC of the Device to Delete.

collectionId              GUID of the Collection to delete all Devices.

or this required & resolution

collectionName            Name of the Collection to delete all Devices.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteDelete DeviceDiskCacheFile

Delete the Disk cache files for a Device.

parameters                  Parameters needed for this Delete.

One of these required

deviceId                  GUID of the Device to Delete Disk cache files.

deviceName                Name of the Device to Delete Disk cache files.

deviceMac                 MAC of the Device to Delete Disk cache files.

This required

diskLocatorId             GUID of the Disk Locator to Delete Disk cache files.

or this required & resolution

diskLocatorName           Name of the Disk Locator File to Delete Disk cache files.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteDelete DiskLocator

Delete one or more Disk Locators.

parameters                  Parameters needed for this Delete.

This required

diskLocatorId             GUID of the Disk Locator to Delete.

or one of these required & resolutions

diskLocatorName           Name of the Disk Locator File to Delete.

storeId                   GUID of the Store to delete all DiskLocators.

storeName                 Name of the Store to delete all DiskLocators.

Optional

deleteDiskFile            1 if the Disk File should be deleted, 0 otherwise. Default=0

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteDelete DiskUpdateDevice

Delete a Disk Update Device.

parameters                  Parameters needed for this Delete.

One of these required

deviceId                  GUID of the Disk Update Device to Delete.

deviceName                Name of the Disk Update Device to Delete.

deviceMac                 MAC of the Disk Update Device to Delete.

### ExecuteDelete DiskVersion

Remove the latest Disk version or no longer needed version if no Devices are currently booted from that version.

parameters                  Parameters needed for this Delete.

This required

diskLocatorId             GUID of the Disk Locator to Delete the Version from.

or this required & resolution

diskLocatorName           Name of the Disk Locator File to Delete the Version from.

Optional

version                   Specifies the version that should be deleted. Used when deleting versions that are no longer needed because of a Merge.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteDelete FarmView

Delete a View from the Farm.

parameters                  Parameters needed for this Delete.

One of these required

farmViewId                GUID of the Farm View to Delete.

farmViewName              Name of the Farm View to Delete.

### ExecuteDelete Server

Delete a Server.

parameters                  Parameters needed for this Delete.

One of these required

serverId                  GUID of the Server to Delete.

serverName                Name of the Server to Delete.

### ExecuteDelete ServerStore

Delete the connection from a Server to a Store.

parameters                  Parameters needed for this Delete.

One of these required

serverId                  GUID of a Server that uses the path to get to the Store.

serverName                Name of a Server that uses the path to get to the Store.

One of these required

storeId                   GUID of the Store.

storeName                 Name of the Store.

### ExecuteDelete Site

Delete a Site.

parameters                  Parameters needed for this Delete.

One of these required

siteId                    GUID of the Site to Delete.

siteName                  Name of the Site to Delete.

### ExecuteDelete SiteView

Delete a View from a Site.

parameters                  Parameters needed for this Delete.

This required

siteViewId                GUID of the Site View to Delete.

or this required & resolution

siteViewName              Name of the Site View to Delete.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteDelete Store

Delete a Store.

parameters                  Parameters needed for this Delete.

One of these required

storeId                   GUID of the Store to Delete.

storeName                 Name of the Store to Delete.

### ExecuteDelete UpdateTask

Delete an Update Task from a Site.

parameters                  Parameters needed for this Delete.

This required

updateTaskId              GUID of the Update Task to Delete.

or this required & resolution

updateTaskName            Name of the Update Task to Delete.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteDelete VirtualHostingPool

Delete a Virtual Hosting Pool from a Site.

parameters                  Parameters needed for this Delete.

This required

virtualHostingPoolId      GUID of the Virtual Hosting Pool to Delete.

or this required & resolution

virtualHostingPoolName    Name of the Virtual Hosting Pool to Delete.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteDelete VirtualHostingPoolServer

Delete a Virtual Hosting Pool Server from a Site.

parameters                  Parameters needed for this Delete.

This required

virtualHostingPoolId      GUID of the Virtual Hosting Pool to Delete.

This required

serverId                  GUID of the Server to Delete.

## ExecuteGet

MapiReturn ExecuteGet(string command,

List<KeyValuePair<string, string>> parameters,

string sortField,

bool ascending,

List<string> fields,

out List<List<KeyValuePair<string, string>>> records);

### ExecuteGet AdDomains

Get all of the available Active Directory domains.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

name                      Name of the Domain.

records                     If successful, records retrieved.

### ExecuteGet AuditActionParameters

Get the Parameters of an Audit Action.

parameters                  Parameters needed for the Get.

This required

auditActionId             GUID of the Audit Action to Get Parameters for.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

auditParameterName        Name of the parameter. Max Length=50

value                     Value of the parameter. Max Length=1000

records                     If successful, records retrieved.

### ExecuteGet AuditActionProperties

Get the Properties of an Audit Action.

parameters                  Parameters needed for the Get.

This required

auditActionId             GUID of the Audit Action to Get Properties for.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

auditPropertyName         Name of the property. Max Length=50

oldValue                  Previous value of the Property. Default=null Max Length=1000

newValue                  New value of the Property. Default=null Max Length=1000

records                     If successful, records retrieved.

### ExecuteGet AuditActionSibling

Get the Sibling of an Audit Action. It is the 2nd object involved with the action.

parameters                  Parameters needed for the Get.

This required

auditActionId             GUID of the Audit Action to Get Sibling for.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

auditActionId             GUID of the action. Length=36

type                      Type of object that action was performed on. Values are: 1 (AuthGroup), 2 (Collection), 3 (Device), 4 (Disk), 5 (DiskLocator), 6 (Farm), 7 (FarmView), 8 (Server), 9 (Site), 10 (SiteView), 11 (Store), 12 (System), and 13 (UserGroup)

objectId                  GUID of the object of the action. Length=36

objectName                Name of the object of the action. Max Length=1000

path                      Path of the object of the action. An example is Site\\Collection for a Device. Default=null Max Length=101

siteId                    GUID of the Site for the object of the action. Empty when not valid. Default=null Length=36

subId                     GUID of the Collection or Store of the action. Empty when not valid. Default=null Length=36

records                     If successful, records retrieved.

### ExecuteGet AuditTrail

Get the Audit Trail actions for a Farm, Site, Server, DiskLocator, Collection, Device, User Group, Site View, Farm View or Store. All Audit Trail actions are returned if no parameters are passed. The result can be filtered by parent, user\\domain and date range.

parameters                  Parameters needed for the Get.

One of these optional

auditActionId             GUID of the Audit Action to Get.

parentId                  Parent auditActionId of the records to retrieve. If no parameters are included, only records with no parent are returned.

rootId                    Root auditActionId of the records to retrieve. All of the actions caused by the root action are returned. If no parameters are included, only records with no root are returned.

siteId                    GUID of the Site to get the Audit Trail for.

siteName                  Name of the Site to get the Audit Trail for.

collectionId              GUID of the Collection to get the Audit Trail for.

siteViewId                GUID of the Site View to get the Audit Trail for.

farmViewId                GUID of the Farm View to get the Audit Trail for.

farmViewName              Name of the Farm View to get the Audit Trail for.

serverId                  GUID of the Server to get the Audit Trail for.

serverName                Name of the Server to get the Audit Trail for.

deviceId                  GUID of the Device to get the Audit Trail for.

deviceName                Name of the Device to get the Audit Trail for.

deviceMac                 MAC of the Device to get the Audit Trail for.

storeId                   GUID of the Store to get the Audit Trail for.

storeName                 Name of the Store to get the Audit Trail for.

diskLocatorId             GUID of the DiskLocator to get the Audit Trail for.

or one of these optional & resolutions

collectionName            Name of the Collection to get the Audit Trail for.

siteViewName              Name of the Site View to get the Audit Trail for.

diskLocatorName           Name of the DiskLocator to get the Audit Trail for.

Optional

userName                  User that performed the action.

domain                    Domain of the user that performed the action.

beginDate                 Date of the first actions to get. If not included, all actions until the endDate are returned. If neither this or the endDate are included, then only actions that occurred in the last week are returned. Format is: yyyy/mm/dd

endDate                   Date of the last actions to get. If not included, all actions from the beginDate until now are returned. If neither this or the beginDate are included, then only actions that occurred in the last week are returned. Format is: yyyy/mm/dd

type                      Comma delimited list of types to get. Values are listed in the type field description.

action                    Comma delimited list of actions to get. Values are listed in the action field description.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

auditActionId             GUID of the action. Length=36

time                      Date/Time the action occurred down to the millisecond. Format is: YYYY-MM-DD HH:MM:SS.SSS Default=getdate

userName                  User that performed the action. Max Length=255

domain                    Domain of the user that performed the action. Max Length=255

type                      Type of object that action was performed on. Values are: 0 (Many), 1 (AuthGroup), 2 (Collection), 3 (Device), 4 (Disk), 5 (DiskLocator), 6 (Farm), 7 (FarmView), 8 (Server), 9 (Site), 10 (SiteView), 11 (Store), 12 (System), and 13 (UserGroup)

action                    Name of the action taken. This is a number that is converted to a string for display. Values are: 1 (AddAuthGroup), 2 (AddCollection), 3 (AddDevice), 4 (AddDiskLocator), 5 (AddFarmView), 6 (AddServer), 7 (AddSite), 8 (AddSiteView), 9 (AddStore), 10 (AddUserGroup), 11 (AddVirtualHostingPool), 12 (AddUpdateTask), 13 (AddDiskUpdateDevice), 1001 (DeleteAuthGroup), 1002 (DeleteCollection), 1003 (DeleteDevice), 1004 (DeleteDeviceDiskCacheFile), 1005 (DeleteDiskLocator), 1006 (DeleteFarmView), 1007 (DeleteServer), 1008 (DeleteServerStore), 1009 (DeleteSite), 1010 (DeleteSiteView), 1011 (DeleteStore), 1012 (DeleteUserGroup), 1013 (DeleteVirtualHostingPool), 1014 (DeleteUpdateTask), 1015 (DeleteDiskUpdateDevice), 1016 (DeleteDiskVersion), 2001 (RunAddDeviceToDomain), 2002 (RunApplyAutoUpdate), 2003 (RunApplyIncrementalUpdate), 2004 (RunArchiveAuditTrail), 2005 (RunAssignAuthGroup), 2006 (RunAssignDevice), 2007 (RunAssignDiskLocator), 2008 (RunAssignServer), 2009 (RunWithReturnBoot), 2010 (RunCopyPasteDevice), 2011 (RunCopyPasteDisk), 2012 (RunCopyPasteServer), 2013 (RunCreateDirectory), 2014 (RunCreateDiskCancel), 2015 (RunDisableCollection), 2016 (RunDisableDevice), 2017 (RunDisableDeviceDiskLocator), 2018 (RunDisableDiskLocator), 2019 (RunDisableUserGroup), 2020 (RunDisableUserGroupDiskLocator), 2021 (RunWithReturnDisplayMessage), 2022 (RunEnableCollection), 2023 (RunEnableDevice), 2024 (RunEnableDeviceDiskLocator), 2025 (RunEnableDiskLocator), 2026 (RunEnableUserGroup), 2027 (RunEnableUserGroupDiskLocator), 2028 (RunExportOemLicenses), 2029 (RunImportDatabase), 2030 (RunImportDevices), 2031 (RunImportOemLicenses), 2032 (RunMarkDown), 2033 (RunWithReturnReboot), 2034 (RunRemoveAuthGroup), 2035 (RunRemoveDevice), 2036 (RunRemoveDeviceFromDomain), 2037 (RunRemoveDirectory), 2038 (RunRemoveDiskLocator), 2039 (RunResetDeviceForDomain), 2040 (RunResetDatabaseConnection), 2041 (RunRestartStreamingService), 2042 (RunWithReturnShutdown), 2043 (RunStartStreamingService), 2044 (RunStopStreamingService), 2045 (RunUnlockAllDisk), 2046 (RunUnlockDisk), 2047 (RunServerStoreVolumeAccess), 2048 (RunServerStoreVolumeMode), 2049 (RunMergeDisk), 2050 (RunRevertDiskVersion), 2051 (RunPromoteDiskVersion), 2052 (RunCancelDiskMaintenance), 2053 (RunActivateDevice), 2054 (RunAddDiskVersion), 2055 (RunExportDisk), 2056 (RunAssignDisk), 2057 (RunRemoveDisk), 2058 (RunDiskUpdateStart), 2059 (RunDiskUpdateCancel), 2060 (RunSetOverrideVersion), 2061 (RunCancelTask), 2062 (RunClearTask), 2063 (RunForceInventory), 2064 RunUpdateBDM, 2065 (RunStartDeviceDiskTempVersionMode), 2066 (RunStopDeviceDiskTempVersionMode), 3001 (RunWithReturnCreateDisk), 3002 (RunWithReturnCreateDiskStatus), 3003 (RunWithReturnMapDisk), 3004 (RunWithReturnRebalanceDevices), 3005 (RunWithReturnCreateMaintenanceVersion), 3006 (RunWithReturnImportDisk), 4001 (RunByteArrayInputImportDevices), 4002 (RunByteArrayInputImportOemLicenses), 5001 (RunByteArrayOutputArchiveAuditTrail), 5002 (RunByteArrayOutputExportOemLicenses), 6001 (SetAuthGroup), 6002 (SetCollection), 6003 (SetDevice), 6004 (SetDisk), 6005 (SetDiskLocator), 6006 (SetFarm), 6007 (SetFarmView), 6008 (SetServer), 6009 (SetServerBiosBootstrap), 6010 (SetServerBootstrap), 6011 (SetServerStore), 6012 (SetSite), 6013 (SetSiteView), 6014 (SetStore), 6015 (SetUserGroup), 6016 SetVirtualHostingPool, 6017 SetUpdateTask, 6018 SetDiskUpdateDevice, 7001 (SetListDeviceBootstraps), 7002 (SetListDeviceBootstrapsDelete), 7003 (SetListDeviceBootstrapsAdd), 7004 (SetListDeviceCustomProperty), 7005 (SetListDeviceCustomPropertyDelete), 7006 (SetListDeviceCustomPropertyAdd), 7007 (SetListDeviceDiskPrinters), 7008 (SetListDeviceDiskPrintersDelete), 7009 (SetListDeviceDiskPrintersAdd), 7010 (SetListDevicePersonality), 7011 (SetListDevicePersonalityDelete), 7012 (SetListDevicePersonalityAdd), 7013 (SetListDiskLocatorCustomProperty), 7014 (SetListDiskLocatorCustomPropertyDelete), 7015 (SetListDiskLocatorCustomPropertyAdd), 7016 (SetListServerCustomProperty), 7017 (SetListServerCustomPropertyDelete), 7018 (SetListServerCustomPropertyAdd), 7019 (SetListUserGroupCustomProperty), 7020 (SetListUserGroupCustomPropertyDelete), and 7021 (SetListUserGroupCustomPropertyAdd)

objectId                  GUID of the object of the action. Default=null Length=36

objectName                Name of the object of the action. Default=null Max Length=1000

path                      Path of the object of the action. An example is Site\\Collection for a Device. Default=null Max Length=101

siteId                    GUID of the Site for the object of the action. Empty when not valid. Default=null Length=36

subId                     GUID of the Collection or Store of the action. Empty when not valid. Default=null Length=36

parentId                  GUID of the parent action (one that triggered this action) if one exists. Empty when not valid. Default=null Length=36

rootId                    GUID of the root action (one that triggered this group of actions) if one exists. Empty when not valid. Default=null Length=36

attachments               An or'ed value that indicates if there are any details for this action. A value of 15 indicates that there are Children, Sibling, Parameters and Properties for the action. Values are: 0 (None), 1 (Children), 2 (Sibling), 4 (Parameters), and 8 (Properties) Default=0

records                     If successful, records retrieved.

### ExecuteGet AuthGroup

Get the fields for an AuthGroup, all AuthGroups in the system, AuthGroups with Farm, Site or Collection Authorization. All AuthGroups in the system are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

authGroupId               GUID of the AuthGroup to Get.

authGroupName             Name of the AuthGroup to Get.

siteId                    GUID of the Site to Get all AuthGroups with Authorization for.

siteName                  Name of the Site to Get all AuthGroups with Authorization for.

collectionId              GUID of the Collection to Get all AuthGroups with Authorization for.

or this optional & resolution

collectionName            Name of the Collection to Get all AuthGroups with Authorization for.

Optional

farm                      1 if AuthGroups with Farm Authorization should be returned, 0 otherwise.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

authGroupName             Name of the Active Directory or Windows Group. Max Length=450

description               User description. Default="" Max Length=250

fields                      List of fields to retrieve, if not included, all fields are retrieved.

authGroupId               Read-only GUID that uniquely identifies this AuthGroup. Length=36

authGroupName             Name of the Active Directory or Windows Group. Max Length=450

description               User description. Default="" Max Length=250

role                      Role of the AuthGroup for a Collection. role can only be used with collectionId or collectionName. 300 is Collection Administrator, and 400 is Collection Operator. Default=999

records                     If successful, records retrieved.

### ExecuteGet AuthGroupUsage

Get the items that are authorized for an AuthGroup.

parameters                  Parameters needed for the Get.

One of these required

authGroupId               GUID of the AuthGroup to Get all items that are authorized for it.

authGroupName             Name of the AuthGroup to Get all items that are authorized for it.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

id                        GUID of the item. The item can be a Farm, Site or Collection. It will be empty for Farm.

name                      Name of the item. The item can be a Farm, Site or Collection.

role                      Role of the AuthGroup for the item. 100 is Farm Administrator, 200 is Site Administrator, 300 is Collection Administrator, and 400 is Collection Operator. Default=999

records                     If successful, records retrieved.

### ExecuteGet CeipData

Get the CEIP configuration

parameters                  Parameters needed for the Get.

Optional

uuid                      CEIP UUID of this Farm. This is optional since there is only one.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

enabled                   1 if CEIP is enabled, otherwise 0. Min=0, Max=1

uuid                      CEIP UUID. Length=36

nextUpload                Date and time next CEIP upload is due if enabled is 1. Default=null

inProgress                1 if an upload is currently in progress, otherwise 0. Default=0

serverId                  ID of server that is currently uploading, null if inProgress is 0. Default=null Length=36

oneTimeUpload             1 to perform a one time upload. Default=0

records                     If successful, records retrieved.

### ExecuteGet CisData

Get the CIS configuration

fields                      List of fields to retrieve, if not included, all fields are retrieved.

cisDataId                 CIS UUID Length=36

userName                  Username used to obtain the token Default=null Max Length=255

uploadToken               Token for uploading bundles to CIS Default=null Max Length=10

path                      Path where the last problem report bundle was saved Default=null Max Length=255

password                  Password of the user required to obtain the token. This is required only by Set and Add

records                     If successful, records retrieved.

### ExecuteGet Collection

Get the fields for a Collection or all Collections in a Site or Farm. All Collections are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

collectionId              GUID of the Collection to Get.

siteId                    GUID of the Site to Get all Collections for.

siteName                  Name of the Site to Get all Collections for.

or this optional & resolution

collectionName            Name of the Collection to Get.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

collectionName            Name of the Collection. It is unique within the Site. Max Length=50

description               User description. Default="" Max Length=250

deviceCount               Read-only count of Devices in this Collection. Default=0

deviceWithPVDCount        Read-only count of Devices with Personal vDisk in this Collection. Default=0

activeDeviceCount         Read-only count of active Devices in this Collection. Default=0

fields                      List of fields to retrieve, if not included, all fields are retrieved.

collectionId              Read-only GUID that uniquely identifies this Collection. Length=36

collectionName            Name of the Collection. It is unique within the Site. Max Length=50

siteId                    GUID of the Site that this Collection is a member of. It is not used with siteName. Length=36

siteName                  Name of the Site that this Collection is a member of. It is not used with siteId.

description               User description. Default="" Max Length=250

templateDeviceId          GUID of a Device in the Collection whose settings are used for initial values of new Devices. Not used with templateDeviceName. Default=null Length=36

templateDeviceName        Name of a Device in the Collection whose settings are used for initial values of new Devices. Not used with templateDeviceId. Default=null

lastAutoAddDeviceNumber   The Device Number of the last Auto Added Device. Default=0

enabled                   1 when Devices in the Collection can be booted, 0 otherwise. Default=1

deviceCount               Read-only count of Devices in this Collection. Default=0

deviceWithPVDCount        Read-only count of Devices with Personal vDisk in this Collection. Default=0

activeDeviceCount         Read-only count of active Devices in this Collection. Default=0

makActivateNeededCount    Read-only count of active Devices that need MAK activation in this Collection. Default=0

autoAddPrefix             The string put before the Device Number for Auto Add. Default=null ASCII computer name characters no end digit Max Length=12

autoAddSuffix             The string put after the Device Number for Auto Add. Default=null ASCII computer name characters no begin digit Max Length=12

autoAddZeroFill           1 when zeros be placed before the Device Number up to the autoAddNumberLength for Auto Add, 0 otherwise. Default=1

autoAddNumberLength       The maximum length of the Device Number for Auto Add. This length plus the autoAddPrefix length plus the autoAddSuffix length must be less than 16. Required that ((lenautoAddPrefix+lenautoAddSuffix)+autoAddNumberLength)<=15. Min=3, Max=9, Default=4

role                      Read-only Role of the user for this item. 100 is Farm Administrator, 200 is Site Administrator, 300 is Collection Administrator, and 400 is Collection Operator. Default=999

records                     If successful, records retrieved.

### ExecuteGet CommandDescription

Return one or more commands with description.

parameters                  Parameters needed for the Get.

This required

Action                    Action to get commands with description for.

Optional

Type                      Command Type of the Action to get a description for.

ObjectType                Object Type to get command descriptions for. Valid Object Types are: Many, AuthGroup, Collection, Device, Disk, DiskLocator, Farm, FarmView, Server, Site, SiteView, Store, and System.

IType                     Interface Type to get command descriptions for. Values are: 0 (Mcli), 1 (PowerShell), 2 (SoapServer). Default=0

Culture                   Optional culture to use for the command descriptions returned.

records                     If successful, records retrieved.

### ExecuteGet CommandFields

Return one record with fields and descriptions.

parameters                  Parameters needed for the Get.

This required

Action                    Action to get fields.

This required

Type                      Type of the Action to get fields.

Optional

Culture                   Optional culture to use for the field descriptions returned.

records                     If successful, records retrieved.

### ExecuteGet CommandParameters

Return records with parameter type, parameters and descriptions. Parameter types that maybe returned include: Optional, RequiredSingle, OptionalSingle, RequiredSingleAmbiguous, OptionalSingleAmbiguous, and Resolution.

parameters                  Parameters needed for the Get.

This required

Action                    Action to get parameters.

This required

Type                      Type of the Action to get parameters.

Optional

Culture                   Optional culture to use for the parameter descriptions returned.

records                     If successful, records retrieved.

### ExecuteGet CommandSortFields

Return one record with sort fields and descriptions.

parameters                  Parameters needed for the Get.

This required

Action                    Action to get sort fields.

This required

Type                      Type of the Action to get sort fields.

Optional

Culture                   Optional culture to use for the sort field descriptions returned.

records                     If successful, records retrieved.

### ExecuteGet CommandStandardParameters

Return one record with standard parameter types and descriptions. Parameter types that maybe returned include: parameters, fields, record, records, sortField, resultId, rv, startPosition, maxRecords, totalCount, dataIn, dataOut, and commands.

parameters                  Parameters needed for the Get.

This required

Action                    Action to get standard parameter types and descriptions.

This required

Type                      Type of the Action to get standard parameter types and descriptions.

Optional

Culture                   Optional culture to use for the standard parameter descriptions returned.

records                     If successful, records retrieved.

### ExecuteGet Device

Get the fields for a Device, all Devices in a Collection, Site, Farm View, or Farm. All Devices are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

deviceId                  GUID of the Device to Get.

deviceName                Name of Device to Get.

deviceMac                 MAC of the Device to Get.

collectionId              GUID of the Collection to Get all Devices for.

serverId                  GUID of the Server to Get all Devices for.

serverName                Name of the Server to Get all Devices for.

diskLocatorId             GUID of the DiskLocator to Get all Devices for.

siteViewId                GUID of the Site View to Get all Devices for.

siteId                    GUID of the Site.

siteName                  Name of the Site.

farmViewId                GUID of the Farm View to Get all Devices for.

farmViewName              Name of the Farm View to Get all Devices for.

bdmBoot                   Include only the BDM Devices when set to 1. PXE devices if set to 0. If not included, all Devices are returned.

deviceIdList              Comma delimited list of GUIDs of the Devices to Get. Maximum length is 8000 characters.

deviceNameList            Comma delimited list of Names of the Devices to Get. Maximum length is 8000 characters.

deviceMacList             Comma delimited list of MACs of the Devices to Get. Maximum length is 8000 characters.

or one of these optional & resolutions

collectionName            Name of the Collection to Get all Devices for.

diskLocatorName           Name of the DiskLocator to Get all Devices for.

siteViewName              Name of the Site View to Get all Devices for.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

deviceName                Computer name with no spaces. ASCII computer name characters Max Length=15

description               User description. Default="" Max Length=250

deviceMac                 Ethernet address as a string in the form XX-XX-XX-XX-XX-XX. Uniquely identifies the Device. Length=17

bootFrom                  Device to boot from. Choices are 1 for vDisk, 2 for Hard Disk, and 3 for Floppy. This cannot be Set for a Device with Personal vDisk. Min=1, Max=3, Default=1

className                 Used by Automatic Update feature to match new versions of Disks to a Device. This cannot be Set for a Device with Personal vDisk. Default="" Max Length=41

port                      UDP port to use with Stream Service. Min=1025, Max=65534, Default=6901

fields                      List of fields to retrieve, if not included, all fields are retrieved.

deviceId                  Read-only GUID that uniquely identifies this Device. Length=36

deviceName                Computer name with no spaces. ASCII computer name characters Max Length=15

collectionId              GUID of the Collection this Device is to be a member of. It is not used with collectionName. Length=36

collectionName            Name of the Collection this Device is to be a member of. siteName or siteId must also be used.

siteId                    GUID of the Site the collectionName is to be a member of. This or siteName is used with collectionName.

siteName                  Name of the Site the collectionName is to be a member of. This or siteId is used with collectionName.

description               User description. Default="" Max Length=250

deviceMac                 Ethernet address as a string in the form XX-XX-XX-XX-XX-XX. Uniquely identifies the Device. Length=17

bootFrom                  Device to boot from. Choices are 1 for vDisk, 2 for Hard Disk, and 3 for Floppy. This cannot be Set for a Device with Personal vDisk. Min=1, Max=3, Default=1

className                 Used by Automatic Update feature to match new versions of Disks to a Device. This cannot be Set for a Device with Personal vDisk. Default="" Max Length=41

port                      UDP port to use with Stream Service. Min=1025, Max=65534, Default=6901

enabled                   1 when it can be booted, 0 otherwise. This cannot be Set for a Device with Personal vDisk. Default=1

localDiskEnabled          If there is a local disk menu choice for the Device, this is 1. This cannot be Set for a Device with Personal vDisk. Default=0

role                      Read-only Role of the user for this item. 100 is Farm Administrator, 200 is Site Administrator, 300 is Collection Administrator, and 400 is Collection Operator. Default=999

authentication            Device log in authentication. Choices are 0 for none, 1 for User Name/Password, and 2 for Extern. This cannot be Set for a Device with Personal vDisk. Min=0, Max=2, Default=0

user                      Name of user to authenticate before the boot process continues. This cannot be Set for a Device with Personal vDisk. Default="" ASCII Max Length=20

password                  Password of user to authenticate before the boot process continues. This cannot be Set for a Device with Personal vDisk. Default="" ASCII Max Length=100

active                    1 if the Device is currently active, 0 otherwise. Default=0

template                  1 if the Device is the template in its Collection, 0 otherwise. Default=0

adTimestamp               The time the Active Directory machine account password was generated. Do not set this field, it is only set internally by PVS. Default=0

adSignature               The signature of the Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default=0

adPassword                The Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default="" ASCII Max Length=256

logLevel                  Level to perform logging at. Values are: 0 (None), 1 (Fatal), 2 (Error), 3 (Warning), 4 (Info), 5 (Debug), and 6 (Trace). Min=0, Max=6, Default=0

domainName                Fully qualified name of the domain that the Device belongs to. Do not set this field, it is only set internally by PVS. Default=null Max Length=255

domainObjectSID           The value of the objectSID AD attribute of the same name for the Device's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=186

domainControllerName      The name of the DC used to create the host's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=4000

domainTimeCreated         The time that the computer account was created. Do not set this field, it is only set internally by PVS. Format is: YYYY-MM-DD HH:MM:SS.SSS Default=null

type                      1 when it performs test of Disks, 2 when it performs maintenance on Disks, 3 when it has a Personal vDisk, 4 when it has a Personal vDisk and performs tests, 0 otherwise. Min=0, Max=4, Default=0

pvdDriveLetter            Read-only Personal vDisk Drive letter. Range is E to U and W to Z. Default=null Max Length=1

localWriteCacheDiskSize   The size in GB to format the Device cache file disk. If the value is 0, then the disk is not formatted. Min=0, Max=2048, Default=0

virtualHostingPoolId      GUID that uniquely identifies the Virtual Hosting Pool for a VM. This is needed when Adding a VM device. Default=null Length=36

hypVmId                   Hypervisor VM ID for HCL Default=null Max Length=250

temporaryVersionSet       Read-only 1 when temporary version is set. Default=0

bdmBoot                   Use PXE boot when set to 0, BDM boot when set to 1. Default is PXE Default=0

bdmType                   Use PXE boot when set to 0, BDM (Bios) boot when set to 1 and BDM (Uefi) boot when set to 2.  Default=0

bdmFormat                 1 use VHD for BDMboot, 2 use ISO, 3 use USB. Default=0

bdmUpdated                Timestamp of the last BDM boot disk update. Default=null

bdmCreated                Timstamp when BDM device was created  Default=null

xsPvsProxyUuid            UUID of XenServer PVS\_proxy Default=null Length=36

records                     If successful, records retrieved.

### ExecuteGet DeviceBootstraps

Get all Bootstrap files for a Device, and the menuText for each.

parameters                  Parameters needed for the Get.

One of these required

deviceId                  GUID of the Device.

deviceName                Name of the Device.

deviceMac                 MAC of the Device.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

bootstrap                 Name of the bootstrap file. Max Length=259

fields                      List of fields to retrieve, if not included, all fields are retrieved.

bootstrap                 Name of the bootstrap file. Max Length=259

menuText                  Text that is displayed in the Boot Menu. If this field has no value, the bootstrap value is used. Default="" ASCII Max Length=64

records                     If successful, records retrieved.

### ExecuteGet DeviceCustomProperty

Get the Device Custom Property names and values.

parameters                  Parameters needed for the Get.

One of these required

deviceId                  GUID of the Device.

deviceName                Name of the Device.

deviceMac                 MAC of the Device.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

name                      Name of the Device custom property. Max Length=250

fields                      List of fields to retrieve, if not included, all fields are retrieved.

name                      Name of the Device custom property. Max Length=250

value                     Value of the Device custom property. Max Length=1000

records                     If successful, records retrieved.

### ExecuteGet DeviceDiskPrinters

Get all non-disabled Printers for a Device/Disk, and the setting for each.

parameters                  Parameters needed for the Get.

One of these required

deviceId                  GUID of the Device.

deviceName                Name of the Device.

deviceMac                 MAC of the Device.

This required

diskLocatorId             GUID of the Disk Locator.

or this required & resolution

diskLocatorName           Name of the Disk Locator File.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

name                      Name of the Printer. Must come from the list of Printers available on the Disk.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

name                      Name of the Printer. Must come from the list of Printers available on the Disk.

state                     Valid states are 1 (enabled network), 2 (enabled local), or 3 (default). 0 (disabled) can be used when setting a Printer that used to be 1 or 2 to 0. The list of all Printers available come from the Disk. Min=0, Max=3

records                     If successful, records retrieved.

### ExecuteGet DeviceDiskTempVersion

Get Temporary Disk Version information for a Device, DiskLocator, Disk Version, Site or Farm.

parameters                  Parameters needed for the Get.

One of these optional

deviceId                  GUID of the Device to get the temporary disk version information for.

deviceName                Name of the Device to get the temporary disk version information for.

deviceMac                 MAC of the Device to get the temporary disk version information for.

siteId                    GUID of the Site to get temporary disk version information for, and also resolution for diskLocatorName.

siteName                  Name of the Site to get temporary disk version information for, and also resolution for diskLocatorName.

diskLocatorId             GUID of the Disk Locator to get temporary disk version information for.

or this optional & resolution

diskLocatorName           Name of the Disk Locator to get temporary disk version information for.

This optional & resolution

version                   Version of the DiskLocator specified to get temporary disk version information for. Needs the diskLocatorId or diskLocatorName too.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

deviceName                Read-only Computer name that uniquely identifies the Device with temporary version. ASCII computer name characters

fields                      List of fields to retrieve, if not included, all fields are retrieved.

deviceId                  Read-only GUID that uniquely identifies the Device with temporary version. Length=36

deviceName                Read-only Computer name that uniquely identifies the Device with temporary version. ASCII computer name characters

diskLocatorId             Read-only GUID that uniquely identifies then Disk Locator with temporary version. Length=36

diskLocatorName           Read-only Name of the Disk Locator File with temporary version. It is unique within the Store. ASCII

siteId                    Read-only GUID of the Site the Device and DiskLocator are a member of.

siteName                  Read-only Name of the Site the Device and DiskLocator are a member of.

storeId                   Read-only GUID of the Store that the Disk Locator is a member of.

storeName                 Read-only Name of the Store that the Disk Locator is a member of.

version                   Read-only Disk version the temporary is for.

records                     If successful, records retrieved.

### ExecuteGet DeviceInfo

Get the fields and status for a Device, all Devices in a Collection, Site, Farm View, or Farm. All Devices are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

deviceId                  GUID of the Device to Get.

deviceName                Name of Device to Get.

deviceMac                 MAC of the Device to Get.

collectionId              GUID of the Collection to Get all Devices for.

serverId                  GUID of the Server to Get all Devices for.

serverName                Name of the Server to Get all Devices for.

diskLocatorId             GUID of the DiskLocator to Get all Devices for.

siteViewId                GUID of the Site View to Get all Devices for.

siteId                    GUID of the Site.

siteName                  Name of the Site.

farmViewId                GUID of the Farm View to Get all Devices for.

farmViewName              Name of the Farm View to Get all Devices for.

deviceIdList              Comma delimited list of GUIDs of the Devices to Get. Maximum length is 8000 characters.

deviceNameList            Comma delimited list of Names of the Devices to Get. Maximum length is 8000 characters.

deviceMacList             Comma delimited list of MACs of the Devices to Get. Maximum length is 8000 characters.

bdmBoot                   Include only the BDM Devices when set to 1. PXE devices if set to 0. If not included, all Devices are returned.

or one of these optional & resolutions

collectionName            Name of the Collection to Get all Devices for.

diskLocatorName           Name of the DiskLocator to Get all Devices for.

siteViewName              Name of the Site View to Get all Devices for.

Optional

onlyActive                Include only the active Devices when set to 1. If not included or set to 1, all Devices are returned. Only active Devices are always returned for serverId, serverName, or version.

makLicenseActivated       Optional MAK licensing indicator value to only return active Devices for. Values are: 0 (MAK not used), 1 (Not Activated), 2 (Activated).

version                   Version of the Disk to Get all active Devices for. This is used with diskLocatorId or diskLocatorName.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

deviceName                Computer name with no spaces. ASCII computer name characters Max Length=15

description               User description. Default="" Max Length=250

deviceMac                 Ethernet address as a string in the form XX-XX-XX-XX-XX-XX. Uniquely identifies the Device. Length=17

bootFrom                  Device to boot from. Choices are 1 for vDisk, 2 for Hard Disk, and 3 for Floppy. This cannot be Set for a Device with Personal vDisk. Min=1, Max=3, Default=1

className                 Used by Automatic Update feature to match new versions of Disks to a Device. This cannot be Set for a Device with Personal vDisk. Default="" Max Length=41

port                      UDP port to use with Stream Service. Min=1025, Max=65534, Default=6901

serverName                Read-only Name of the Server that the Device is using. It is equal to "" if the Device is not active.

diskLocatorName           Read-only name of the Disk Locator File that the Device is using. It is equal to the list of Disk Locator names for the Device if the Device is not active.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

deviceId                  Read-only GUID that uniquely identifies this Device. Length=36

deviceName                Computer name with no spaces. ASCII computer name characters Max Length=15

collectionId              GUID of the Collection this Device is to be a member of. It is not used with collectionName. Length=36

collectionName            Name of the Collection this Device is to be a member of. siteName or siteId must also be used.

siteId                    GUID of the Site the collectionName is to be a member of. This or siteName is used with collectionName.

siteName                  Name of the Site the collectionName is to be a member of. This or siteId is used with collectionName.

description               User description. Default="" Max Length=250

deviceMac                 Ethernet address as a string in the form XX-XX-XX-XX-XX-XX. Uniquely identifies the Device. Length=17

bootFrom                  Device to boot from. Choices are 1 for vDisk, 2 for Hard Disk, and 3 for Floppy. This cannot be Set for a Device with Personal vDisk. Min=1, Max=3, Default=1

className                 Used by Automatic Update feature to match new versions of Disks to a Device. This cannot be Set for a Device with Personal vDisk. Default="" Max Length=41

port                      UDP port to use with Stream Service. Min=1025, Max=65534, Default=6901

enabled                   1 when it can be booted, 0 otherwise. This cannot be Set for a Device with Personal vDisk. Default=1

localDiskEnabled          If there is a local disk menu choice for the Device, this is 1. This cannot be Set for a Device with Personal vDisk. Default=0

role                      Read-only Role of the user for this item. 100 is Farm Administrator, 200 is Site Administrator, 300 is Collection Administrator, and 400 is Collection Operator. Default=999

authentication            Device log in authentication. Choices are 0 for none, 1 for User Name/Password, and 2 for Extern. This cannot be Set for a Device with Personal vDisk. Min=0, Max=2, Default=0

user                      Name of user to authenticate before the boot process continues. This cannot be Set for a Device with Personal vDisk. Default="" ASCII Max Length=20

password                  Password of user to authenticate before the boot process continues. This cannot be Set for a Device with Personal vDisk. Default="" ASCII Max Length=100

active                    1 if the Device is currently active, 0 otherwise. Default=0

template                  1 if the Device is the template in its Collection, 0 otherwise. Default=0

adTimestamp               The time the Active Directory machine account password was generated. Do not set this field, it is only set internally by PVS. Default=0

adSignature               The signature of the Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default=0

adPassword                The Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default="" ASCII Max Length=256

logLevel                  Level to perform logging at. Values are: 0 (None), 1 (Fatal), 2 (Error), 3 (Warning), 4 (Info), 5 (Debug), and 6 (Trace). Min=0, Max=6, Default=0

domainName                Fully qualified name of the domain that the Device belongs to. Do not set this field, it is only set internally by PVS. Default=null Max Length=255

domainObjectSID          nbsp; The value of the objectSID AD attribute of the same name for the Device's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=186

domainControllerName      The name of the DC used to create the host's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=4000

domainTimeCreated         The time that the computer account was created. Do not set this field, it is only set internally by PVS. Format is: YYYY-MM-DD HH:MM:SS.SSS Default=null

type                      1 when it performs test of Disks, 2 when it performs maintenance on Disks, 3 when it has a Personal vDisk, 4 when it has a Personal vDisk and performs tests, 0 otherwise. Min=0, Max=4, Default=0

pvdDriveLetter            Read-only Personal vDisk Drive letter. Range is E to U and W to Z. Default=null Max Length=1

localWriteCacheDiskSize   The size in GB to format the Device cache file disk. If the value is 0, then the disk is not formatted. Min=0, Max=2048, Default=0

virtualHostingPoolId      GUID that uniquely identifies the Virtual Hosting Pool for a VM. This is needed when Adding a VM device. Default=null Length=36

hypVmId                   Hypervisor VM ID for HCL Default=null Max Length=250

temporaryVersionSet       Read-only 1 when temporary version is set. Default=0

bdmBoot                   Use PXE boot when set to 0, BDM boot when set to 1. Default is PXE Default=0

bdmType                   Use PXE boot when set to 0, BDM (Bios) boot when set to 1 and BDM (Uefi) boot when set to 2.  Default=0

bdmFormat                 1 use VHD for BDMboot, 2 use ISO, 3 use USB. Default=0

bdmUpdated                Timestamp of the last BDM boot disk update. Default=null

bdmCreated                Timstamp when BDM device was created  Default=null

xsPvsProxyUuid            UUID of XenServer PVS\_proxy Default=null Length=36

ip                        Read-only IP of the Device. It is equal to "" if the Device is not active.

serverPortConnection      Read-only Port of the Server that the Device is using. It is equal to "" if the Device is not active. Default=0

serverIpConnection        Read-only IP of the Server that the Device is using. It is equal to "" if the Device is not active.

serverId                  Read-only GUID of the Server that the Device is using. It is equal to "" if the Device is not active. Length=36

serverName                Read-only Name of the Server that the Device is using. It is equal to "" if the Device is not active.

diskLocatorId             Read-only GUID of the Disk Locator that the Device is using. It is equal to "" if the Device is not active. Length=36

diskLocatorName           Read-only name of the Disk Locator File that the Device is using. It is equal to the list of Disk Locator names for the Device if the Device is not active.

diskVersion               Read-only version of the Disk Locator File that the Device is using. It is equal to "" if the Device is not active. Default=0

diskVersionAccess         State of the Disk Version. Values are: 0 (Production), 1 (Maintenance), 2 (MaintenanceHighestVersion), 3 (Override), 4 (Merge), 5 (MergeMaintenance), 6 (MergeTest), and 7 (Test). It is equal to "" if the Device is not active. Default=0

diskFileName              Name of the Disk File including the extension. It is equal to "" if the Device is not active.

status                    1 or 2 numbers in the format n,n. They are the number of retries and if ram cache is being used, ram cache percent used. It is equal to "" if the Device is not active.

licenseType               0 when None, 1 for Desktop, 2 for Server, 5 for OEM SmartClient, 6 for XenApp, 7 for XenDesktop. It is equal to 0 if the Device is not active. Default=0

makLicenseActivated       Read-only indicator if MAK licensing is being used and is activated. Values are: 0 (MAK not used), 1 (Not Activated), 2 (Activated). It is equal to "" if the Device is not active. Default=0

model                     Oem Only: Read-only model of the computer. Values are OptiPlex 745, 755, 320, 760, FX160, or Default. It is equal to "" if the Device is not active.

license                   Oem Only: Read-only type of the license. Values are 0 when None, 1 or 2 when Desktop. It is equal to 0 if the Device is not active. Default=0

records                     If successful, records retrieved.

### ExecuteGet DevicePersonality

Get the Device Personality names and values.

parameters                  Parameters needed for the Get.

One of these required

deviceId                  GUID of the Device.

deviceName                Name of the Device.

deviceMac                 MAC of the Device.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

name                      Name of the Device personality item. Max Length=250

fields                      List of fields to retrieve, if not included, all fields are retrieved.

name                      Name of the Device personality item. Max Length=250

value                     Value for the Device personality item. Max Length=1000

records                     If successful, records retrieved.

### ExecuteGet DeviceStatus

Get the DeviceStatus fields for a Device or all Devices for a Server, Disk Locator, or Farm. All Devices are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

deviceId                  GUID of the Device to Get status for.

deviceName                Name of Device to Get status for.

deviceMac                 MAC of the Device to Get status for.

serverId                  GUID of the Server to Get all Device Status for.

serverName                Name of the Server to Get all Device Status for.

diskLocatorId             GUID of the Disk Locator to Get all DeviceStatus for.

collectionId              GUID of the Collection to Get all DeviceStatus for.

or one of these optional & resolutions

diskLocatorName           Name of the Disk Locator File to Get all DeviceStatus for.

collectionName            Name of the Collection to Get all DeviceStatus for.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

deviceName                Read-only Name of the Device. Can be used with Get Device.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

deviceId                  Read-only GUID of the Device. Can be used with Get Device. Length=36

deviceName                Read-only Name of the Device. Can be used with Get Device.

ip                        Read-only IP of the Device.

serverPortConnection      Read-only Port of the Server that the Device is using. Default=0

serverIpConnection        Read-only IP of the Server that the Device is using.

serverId                  Read-only GUID of the Server that the Device is using. Length=36

serverName                Read-only Name of the Server that the Device is using.

diskLocatorId             Read-only GUID of the Disk Locator that the Device is using. Length=36

diskLocatorName           Read-only name of the Disk Locator File that the Device is using.

diskVersion               Read-only version of the Disk Locator File that the Device is using. Default=0

diskVersionAccess         State of the Disk Version. Values are: 0 (Production), 1 (Maintenance), 2 (MaintenanceHighestVersion), 3 (Override), 4 (Merge), 5 (MergeMaintenance), 6 (MergeTest), and 7 (Test) Default=0

diskFileName              Name of the Disk File including the extension.

status                    1 or 2 numbers in the format n,n. They are the number of retries and if ram cache is being used, ram cache percent used.

licenseType               0 when None, 1 for Desktop, 2 for Server, 5 for OEM SmartClient, 6 for XenApp, 7 for XenDesktop. Default=0

makLicenseActivated       Read-only indicator if MAK licensing is being used and is activated. Values are: 0 (MAK not used), 1 (Not Activated), 2 (Activated). Default=0

records                     If successful, records retrieved.

### ExecuteGet Disk

Get the fields for a single disk.

parameters                  Parameters needed for the Get.

This required

diskLocatorId             GUID of the Disk Locator.

or this required & resolution

diskLocatorName           Name of the Disk Locator.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

class                     Class of the Disk. Max Length=40

imageType                 Type of this image (software type). Max Length=40

diskSize                  Read-only size of the image. The value is 0 when it is not available. Default=0

vhdBlockSize              Block size in KB. For VHD it is only used with Dynamic type. Tested sizes for VHD are 512, 2048, and 16384. VHD Min=512, Max=16384, Default=2048. For VHDX it is used for all types. Tested size for VHDX is 32768. VHDX Min=1024, Max= 262144, Default=32768. Default=0

logicalSectorSize         Logical Sector Size. Values are: 512, 4096, Default=512

writeCacheSize            RAM cache size (MB). Not 0 when used with Cache in Device RAM, and Cache in Device RAM with Overflow on Hard Disk. A value of 0 will disable the RAM use for Cache in Device RAM with Overflow on Hard Disk. Min=0, Max=131072, Default=0

autoUpdateEnabled         Automatically update this image for matching Devices when set to 1. Default 0

activationDateEnabled     Use activation date to activate image when set to 1. Default 0

adPasswordEnabled         Enable AD password management when set to 1.

haEnabled                 Enable HA when set to 1.

printerManagementEnabled  Invalid printers will be deleted from the Device when set to 1.

writeCacheType            0 (Private), 1 (Cache on Server), 3 (Cache in Device RAM), 4 (Cache on Device Hard Disk), 7 (Cache on Server, Persistent), 9 (Cache in Device RAM with Overflow on Hard Disk), 10 (Private async), 11(Server persistent async), 12 (Cache in Device RAM with Overflow on Hard Disk async) Min=0, Max=12, Default=0

licenseMode               0 (None), 1 (Multiple Activation Key), or 2 (Key Management Service). Min=0, Max=2, Default=0

accelerateOfficeActivation  Run script to activate office automatically.

activeDate                Date to activate the disk if autoUpdateEnabled and activationDateEnabled are 1. Format is yyyy/mm/dd. Empty when the autoUpdateEnabled or activationDateEnabled are 0.

longDescription           Description of the Disk. Max Length=399

operatingSystem           Operating System of Disk. Max Length=250

osType                    Operating System Type of Disk. Max Length=40

serialNumber              User defined serial number. Max Length=36

date                      User defined date. Max Length=40

author                    User defined author. Max Length=40

title                     User defined title. Max Length=40

company                   User defined company. Max Length=40

internalName              User defined name. Max Length=63

originalFile              User defined original file. Max Length=127

hardwareTarget            User defined hardware target. Max Length=127

majorRelease              User defined major release number. Min=0, Max=4294967295, Default=0

minorRelease              User defined minor release number. Min=0, Max=4294967295, Default=0

build                     User defined build number. Min=0, Max=4294967295, Default=0

clearCacheDisabled        Clear cached secrets disabled.

format                    Format of the image. Values are: 0 (VHD), 1 (VHDX). Default=0

records                     If successful, records retrieved.

### ExecuteGet DiskInfo

Get the fields for a Disk and Disk Locator or all Disks and Disk Locators for a Device, Server, Store, Site, or Farm. All Disks and DiskLocators are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

diskLocatorId             GUID of the Disk Locator to Get.

deviceId                  GUID of the Device to Get all DiskLocators for.

deviceName                Name of the Device to Get all DiskLocators for.

deviceMac                 MAC of the Device to Get all DiskLocators for.

serverId                  GUID of the Server to Get all DiskLocators for.

serverName                Name of the Server to Get all DiskLocators for.

updateTaskId              GUID of the Update Task to Get all DiskLocators for.

siteId                    GUID of the Site to Get all DiskLocators for.

siteName                  Name of the Site to Get all DiskLocators for.

or one of these optional & resolutions

diskLocatorName           Name of the Disk Locator File to Get.

storeId                   GUID of the Store to Get all DiskLocators for.

storeName                 Name of the Store to Get all DiskLocators for.

updateTaskName            Name of the Update Task to Get all DiskLocators for.

One of these optional

single                    Include single server connection when set to 1. If this and All are not included, both connection types are included.

all                       Include all server connections for the store when set to 1. If this and Single are not included, both connection types are included.

Optional

onlyActive                Include only the active DiskLocators when set to 1. If not included or set to 0, all DiskLocators are returned.

updateDevice              Include DiskLocators that have an Update Device when set to 1. Include DiskLocators that do not have an Update Device when set to 0. If this parameter is not included, then all DiskLocators are returned.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

diskLocatorName           Name of the Disk Locator File. It is unique within the Store. ASCII Max Length=52

description               User description. Default="" Max Length=250

menuText                  Text that is displayed in the Boot Menu. If this field has no value, the name value is used. Default="" ASCII Max Length=64

fields                      List of fields to retrieve, if not included, all fields are retrieved.

diskLocatorId             Read-only GUID that uniquely identifies this Disk Locator. Length=36

diskLocatorName           Name of the Disk Locator File. It is unique within the Store. ASCII Max Length=52

siteId                    GUID of the Site this DiskLocator is to be a member of. It is not used with siteName. Length=36

siteName                  Name of the Site this DiskLocator is to be a member of. It is not used with siteId.

storeId                   GUID of the Store that this Disk Locator is a member of. siteName or siteId must also be used. It is not used with storeName. Length=36

storeName                 Name of the Store that this Disk Locator is a member of. siteName or siteId must also be used. It is not used with storeId.

description               User description. Default="" Max Length=250

menuText                  Text that is displayed in the Boot Menu. If this field has no value, the name value is used. Default="" ASCII Max Length=64

serverId                  GUID of the single Server that this Disk Locator is assigned to. It is not used with serverName. Default=null Length=36

serverName                Name of the single Server that this Disk Locator is assigned to. It is not used with serverId. Default=null

enabled                   1 when this disk can be booted, 0 otherwise. Default=1

role                      Read-only Role of the user for this item. 100 is Farm Administrator, 200 is Site Administrator, 300 is Collection Administrator, and 999 is read-only. Default=999

mapped                    1 if the Disk is currently mapped, 0 otherwise. Default=0

enabledForDevice          1 when this disk is enabled for the Device specified, 0 otherwise. This is only returned when a Device is specified. Default=1

active                    1 if the DiskLocator is currently active, 0 otherwise. Default=0

rebalanceEnabled          1 when this Server can automatically rebalance Devices, 0 otherwise. Default=0

rebalanceTriggerPercent   Percent over fair load that triggers a dynamic Device rebalance. Min=5, Max=5000, Default=25

subnetAffinity            Qualifier for subnet affinity when assigning a Server. 0=None, 1=Best Effort, 2=Fixed. Min=0, Max=2, Default=0

diskUpdateDeviceId        GUID of the DiskUpdateDevice that is used when updates are performed. Default=null

diskUpdateDeviceName      Name of the DiskUpdateDevice that is used when updates are performed. Default=null

temporaryVersionSet       Read-only 1 when temporary version(s) are set. Default=0

class                     Class of the Disk. Max Length=40

imageType                 Type of this image (software type). Max Length=40

diskSize                  Read-only size of the image. The value is 0 when it is not available. Default=0

vhdBlockSize              Block size in KB. For VHD it is only used with Dynamic type. Tested sizes for VHD are 512, 2048, and 16384. VHD Min=512, Max=16384, Default=2048. For VHDX it is used for all types. Tested size for VHDX is 32768. VHDX Min=1024, Max= 262144, Default=32768. Default=0

logicalSectorSize         Logical Sector Size. Values are: 512, 4096, Default=512

writeCacheSize            RAM cache size (MB). Not 0 when used with Cache in Device RAM, and Cache in Device RAM with Overflow on Hard Disk. A value of 0 will disable the RAM use for Cache in Device RAM with Overflow on Hard Disk. Min=0, Max=131072, Default=0

autoUpdateEnabled         Automatically update this image for matching Devices when set to 1. Default 0

activationDateEnabled     Use activation date to activate image when set to 1. Default 0

adPasswordEnabled         Enable AD password management when set to 1.

haEnabled                 Enable HA when set to 1.

printerManagementEnabled  Invalid printers will be deleted from the Device when set to 1.

writeCacheType            0 (Private), 1 (Cache on Server), 3 (Cache in Device RAM), 4 (Cache on Device Hard Disk), 7 (Cache on Server, Persistent), 9 (Cache in Device RAM with Overflow on Hard Disk), 10 (Private async), 11(Server persistent async), 12 (Cache in Device RAM with Overflow on Hard Disk async) Min=0, Max=12, Default=0

licenseMode               0 (None), 1 (Multiple Activation Key), or 2 (Key Management Service). Min=0, Max=2, Default=0

accelerateOfficeActivation  Run script to activate office automatically.

activeDate                Date to activate the disk if autoUpdateEnabled and activationDateEnabled are 1. Format is yyyy/mm/dd. Empty when the autoUpdateEnabled or activationDateEnabled are 0.

longDescription           Description of the Disk. Max Length=399

operatingSystem           Operating System of Disk. Max Length=250

osType                    Operating System Type of Disk. Max Length=40

serialNumber              User defined serial number. Max Length=36

date                      User defined date. Max Length=40

author                    User defined author. Max Length=40

title                     User defined title. Max Length=40

company                   User defined company. Max Length=40

internalName              User defined name. Max Length=63

originalFile              User defined original file. Max Length=127

hardwareTarget            User defined hardware target. Max Length=127

majorRelease              User defined major release number. Min=0, Max=4294967295, Default=0

minorRelease              User defined minor release number. Min=0, Max=4294967295, Default=0

build                     User defined build number. Min=0, Max=4294967295, Default=0

clearCacheDisabled        Clear cached secrets disabled.

format                    Format of the image. Values are: 0 (VHD), 1 (VHDX). Default=0

deviceCount               Read-only count of Devices. Default=0

locked                    1 if the Disk is currently locked, 0 otherwise. Default=0

records                     If successful, records retrieved.

### ExecuteGet DiskInventory

Get the fields for Inventory Status of a Disk Version or all Disk Versions for a Disk Locator.

parameters                  Parameters needed for the Get.

This required

diskLocatorId             GUID of the Disk Locator to Get Disk Version Inventory of.

or this required & resolution

diskLocatorName           Name of the Disk Locator to Get Disk Version Inventory of.

Optional

version                   Specific Version to Get.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

version                   Version number. The base disk is version 0, the other version numbers are in part of the file name.

serverId                  GUID of the Server that the Disk Version Inventory is being reported about.

serverName                Name of the Server that the Disk Version Inventory is being reported about.

filePath                  Path used to access the disk version from the Server. Empty if the information is not available.

fileTime                  Date/Time of the date version file. Format is: YYYY-MM-DD HH:MM:SS. 0000-00-00 00:00:00 if the information is not available.

propertiesTime            Date/Time of the disk properties. Format is: YYYY-MM-DD HH:MM:SS. 0000-00-00 00:00:00 if the information is not available.

state                     The number code of the inventory state. Values are: 0 (Up to date), 1 (version file is missing), 2 (version file is out of date), 3 (properties are missing), 4 (properties are out of date), 5 (server is not reachable).

active                    1 if the Server is currently active, 2 if unknown, and 0 otherwise.

records                     If successful, records retrieved.

### ExecuteGet DiskLocator

Get the fields for a Disk Locator or all Disk Locators for a Device, Server, Store, Site, or Farm. All DiskLocators are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

diskLocatorId             GUID of the Disk Locator to Get.

deviceId                  GUID of the Device to Get all DiskLocators for.

deviceName                Name of the Device to Get all DiskLocators for.

deviceMac                 MAC of the Device to Get all DiskLocators for.

serverId                  GUID of the Server to Get all DiskLocators for.

serverName                Name of the Server to Get all DiskLocators for.

updateTaskId              GUID of the Update Task to Get all DiskLocators for.

siteId                    GUID of the Site to Get all DiskLocators for.

siteName                  Name of the Site to Get all DiskLocators for.

or one of these optional & resolutions

diskLocatorName           Name of the Disk Locator File to Get.

storeId                   GUID of the Store to Get all DiskLocators for.

storeName                 Name of the Store to Get all DiskLocators for.

updateTaskName            Name of the Update Task to Get all DiskLocators for.

One of these optional

single                    Include single server connection when set to 1. If this and All are not included, both connection types are included.

all                       Include all server connections for the store when set to 1. If this and Single are not included, both connection types are included.

Optional

onlyActive                Include only the active DiskLocators when set to 1. If not included or set to 0, all DiskLocators are returned.

updateDevice              Include DiskLocators that have an Update Device when set to 1. Include DiskLocators that do not have an Update Device when set to 0. If this parameter is not included, then all DiskLocators are returned.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

diskLocatorName           Name of the Disk Locator File. It is unique within the Store. ASCII Max Length=52

description               User description. Default="" Max Length=250

menuText                  Text that is displayed in the Boot Menu. If this field has no value, the name value is used. Default="" ASCII Max Length=64

fields                      List of fields to retrieve, if not included, all fields are retrieved.

diskLocatorId             Read-only GUID that uniquely identifies this Disk Locator. Length=36

diskLocatorName           Name of the Disk Locator File. It is unique within the Store. ASCII Max Length=52

siteId                    GUID of the Site this DiskLocator is to be a member of. It is not used with siteName. Length=36

siteName                  Name of the Site this DiskLocator is to be a member of. It is not used with siteId.

storeId                   GUID of the Store that this Disk Locator is a member of. siteName or siteId must also be used. It is not used with storeName. Length=36

storeName                 Name of the Store that this Disk Locator is a member of. siteName or siteId must also be used. It is not used with storeId.

description               User description. Default="" Max Length=250

menuText                  Text that is displayed in the Boot Menu. If this field has no value, the name value is used. Default="" ASCII Max Length=64

serverId                  GUID of the single Server that this Disk Locator is assigned to. It is not used with serverName. Default=null Length=36

serverName                Name of the single Server that this Disk Locator is assigned to. It is not used with serverId. Default=null

enabled                   1 when this disk can be booted, 0 otherwise. Default=1

role                      Read-only Role of the user for this item. 100 is Farm Administrator, 200 is Site Administrator, 300 is Collection Administrator, and 999 is read-only. Default=999

mapped                    1 if the Disk is currently mapped, 0 otherwise. Default=0

enabledForDevice          1 when this disk is enabled for the Device specified, 0 otherwise. This is only returned when a Device is specified. Default=1

active                    1 if the DiskLocator is currently active, 0 otherwise. Default=0

rebalanceEnabled          1 when this Server can automatically rebalance Devices, 0 otherwise. Default=0

rebalanceTriggerPercent   Percent over fair load that triggers a dynamic Device rebalance. Min=5, Max=5000, Default=25

subnetAffinity            Qualifier for subnet affinity when assigning a Server. 0=None, 1=Best Effort, 2=Fixed. Min=0, Max=2, Default=0

diskUpdateDeviceId        GUID of the DiskUpdateDevice that is used when updates are performed. Default=null

diskUpdateDeviceName      Name of the DiskUpdateDevice that is used when updates are performed. Default=null

temporaryVersionSet       Read-only 1 when temporary version(s) are set. Default=0

records                     If successful, records retrieved.

### ExecuteGet DiskLocatorCustomProperty

Get the DiskLocator Custom Property names and values.

parameters                  Parameters needed for the Get.

This required

diskLocatorId             GUID of the Disk Locator to Get Custom Properties.

or this required & resolution

diskLocatorName           Name of the Disk Locator File to Get Custom Properties.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

name                      Name of the DiskLocator custom property. Max Length=250

fields                      List of fields to retrieve, if not included, all fields are retrieved.

name                      Name of the DiskLocator custom property. Max Length=250

value                     Value of the DiskLocator custom property. Max Length=1000

records                     If successful, records retrieved.

### ExecuteGet DiskLocatorLock

Get the fields for all the locks of a Disk Locator.

parameters                  Parameters needed for the Get.

This required

diskLocatorId             GUID of the Disk Locator to Get the Locks.

or this required & resolution

diskLocatorName           Name of Disk Locator to Get the Locks.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

exclusive                 1 when the lock is exclusive, 0 when it is shared. Default=0

deviceId                  GUID of the Device that has the lock, will not be included if a Server has the lock.

deviceName                Name of the Device that has the lock, will not be included if a Server has the lock.

serverId                  GUID of the Server that has the lock, will not be included if a Device has the lock.

serverName                Name of the Server that has the lock, will not be included if a Device has the lock.

readOnly                  1 when lock is because file system is read only, 0 when file system is read write Default=0

records                     If successful, records retrieved.

### ExecuteGet DiskPrinters

Get all available Printers for a Disk.

parameters                  Parameters needed for the Get.

This required

diskLocatorId             GUID of the Disk Locator.

or this required & resolution

diskLocatorName           Name of the Disk Locator.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

name                      Read-only Name of the Printer.

network                   1 when the printer is networked, 0 otherwise.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

name                      Read-only Name of the Printer.

network                   1 when the printer is networked, 0 otherwise.

records                     If successful, records retrieved.

### ExecuteGet DiskUpdateDevice

Get the fields and status for a Disk Update Device, or all Disk Update Devices for a Site, Server, DiskLocator or Farm. All Disk Update Devices are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

deviceId                  GUID of the Disk Update Device to Get.

deviceName                Name of Disk Update Device to Get.

deviceMac                 MAC of the Disk Update Device to Get.

serverId                  GUID of the Server to Get all Disk Update Devices for.

serverName                Name of the Server to Get all Disk Update Devices for.

diskLocatorId             GUID of the DiskLocator to Get the Disk Update Device for.

updateTaskId              GUID of the Update Task to Get all Disk Update Devices for.

siteId                    GUID of the Site.

siteName                  Name of the Site.

or one of these optional & resolutions

diskLocatorName           Name of the DiskLocator to Get the Disk Update Device for.

updateTaskName            Name of the Update Task to Get all Disk Update Devices for.

Optional

onlyActive                Include only the active Disk Update Devices when set to 1. If not included or set to 0, all Disk Update Devices are returned. Only active Disk Update Devices are always returned for serverId or serverName.

makLicenseActivated       Optional MAK licensing indicator value to only return active Disk Update Devices for. Values are: 0 (MAK not used), 1 (Not Activated), 2 (Activated).

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

deviceName                Computer name with no spaces. ASCII computer name characters Max Length=15

virtualHostingPoolName    Name of the Virtual Hosting Pool.

diskLocatorName           Name of the Disk Locator File to update with this Device.

description               User description. Default="" Max Length=250

deviceMac                 Ethernet address as a string in the form XX-XX-XX-XX-XX-XX. Uniquely identifies the Device. Length=17

port                      UDP port to use with Stream Service. Min=1025, Max=65534, Default=6901

fields                      List of fields to retrieve, if not included, all fields are retrieved.

deviceId                  Read-only GUID that uniquely identifies this Device. Length=36

deviceName                Computer name with no spaces. ASCII computer name characters Max Length=15

virtualHostingPoolId      GUID of the Virtual Hosting Pool. It is not used with virtualHostingPoolName. Default=null Length=36

virtualHostingPoolName    Name of the Virtual Hosting Pool.

diskLocatorId             GUID of the Disk Locator to update with this Device.

diskLocatorName           Name of the Disk Locator File to update with this Device.

siteId                    GUID of the Site this Disk Update Device is to be a member of.

siteName                  Name of the Site this Disk Update Device is to be a member of.

storeId                   GUID of the Store that the Disk Locator is a member of.

storeName                 Name of the Store that the Disk Locator is a member of.

description               User description. Default="" Max Length=250

deviceMac                 Ethernet address as a string in the form XX-XX-XX-XX-XX-XX. Uniquely identifies the Device. Length=17

port                      UDP port to use with Stream Service. Min=1025, Max=65534, Default=6901

active                    1 if the Device is currently active, 0 otherwise. Default=0

adTimestamp               The time the Active Directory machine account password was generated. Do not set this field, it is only set internally by PVS. Default=0

adSignature               The signature of the Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default=0

logLevel                  Level to perform logging at. Values are: 0 (None), 1 (Fatal), 2 (Error), 3 (Warning), 4 (Info), 5 (Debug), and 6 (Trace). Min=0, Max=6, Default=0

domainName                Fully qualified name of the domain that the Device belongs to. Do not set this field, it is only set internally by PVS. Default=null Max Length=255

domainObjectSID           The value of the objectSID AD attribute of the same name for the Device's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=186

domainControllerName      The name of the DC used to create the host's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=4000

domainTimeCreated         The time that the computer account was created. Do not set this field, it is only set internally by PVS. Format is: YYYY-MM-DD HH:MM:SS.SSS Default=null

adPassword                The Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default="" Max Length=256

ip                        Read-only IP of the Device. It is equal to "" if the Device is not active.

serverPortConnection      Read-only Port of the Server that the Device is using. It is equal to "" if the Device is not active. Default=0

serverIpConnection        Read-only IP of the Server that the Device is using. It is equal to "" if the Device is not active.

serverId                  Read-only GUID of the Server that the Device is using. It is equal to "" if the Device is not active. Length=36

serverName                Read-only Name of the Server that the Device is using. It is equal to "" if the Device is not active.

diskVersion               Read-only version of the Disk Locator File that the Device is using. It is equal to "" if the Device is not active. Default=0

status                    1 or 2 numbers in the format n,n. They are the number of retries and if ram cache is being used, ram cache percent used. It is equal to "" if the Device is not active.

licenseType               0 when None, 1 for Desktop, 2 for Server, 5 for OEM SmartClient, 6 for XenApp, 7 for XenDesktop. It is equal to 0 if the Device is not active. Default=0

makLicenseActivated       Read-only indicator if MAK licensing is being used and is activated. Values are: 0 (MAK not used), 1 (Not Activated), 2 (Activated). It is equal to "" if the Device is not active. Default=0

model                     Oem Only: Read-only model of the computer. Values are OptiPlex 745, 755, 320, 760, FX160, or Default. It is equal to "" if the Device is not active.

license                   Oem Only: Read-only type of the license. Values are 0 when None, 1 or 2 when Desktop. It is equal to 0 if the Device is not active. Default=0

records                     If successful, records retrieved.

### ExecuteGet DiskUpdateStatus

Get the status of an Update Task, or all Update Tasks for a Site or Farm. All Disk Update Tasks are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

updateTaskId              GUID of the Update Task to Get.

deviceId                  GUID of the Disk Update Device to Get Disk Update Status for.

deviceName                Name of the Disk Update Device to Get Disk Update Status for.

deviceMac                 MAC of the Disk Update Device to Get Disk Update Status for.

diskUpdateTaskId          GUID of the Disk Update Task and Device relationship to Get Disk Update Status for.

siteId                    GUID of the Site to Get all Update Tasks for. Also used with updateTaskName.

siteName                  Name of the Site to Get all Update Tasks for. Also used with updateTaskName.

or this optional & resolution

updateTaskName            Name of the Update Task to Get.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

updateTaskName            Name of the Update Task.

description               User description of the Update Task.

diskLocatorName           Name of the Disk Locator File to update.

virtualHostingPoolName    Name of the Virtual Hosting Pool being used for the update.

deviceName                Name of the Device being used to do the update.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

diskUpdateTaskId          GUID that uniquely identifies this Update Task and Device relationship. Length=36

updateTaskId              GUID that uniquely identifies the Update Task. Length=36

updateTaskName            Name of the Update Task.

description               User description of the Update Task.

diskLocatorId             GUID of the Disk Locator to update.

diskLocatorName           Name of the Disk Locator File to update.

virtualHostingPoolId      GUID of the Virtual Hosting Pool being used for the update.

virtualHostingPoolName    Name of the Virtual Hosting Pool being used for the update.

deviceId                  GUID that Device being used to do the update.

deviceName                Name of the Device being used to do the update.

siteId                    GUID of the Site that this Update Task Name is a member of.

siteName                  Name of the Site that this Update Task Name is a member of.

storeId                   GUID of the Store that the Disk Locator is a member of.

storeName                 Name of the Store that the Disk Locator is a member of.

previousResult            Status of the last run. Values are: 0 (Ready), 1 (Update Pending), 2 (Preparing Image), 3 (Starting VM), 4 (Update In Progress), 5 (Stopping VM), 6 (Submitting Image), 7 (Reverting Image), 8 (Invalid), 9 (Aborted), 10 (Completed Successfully), 11 (No Updates) Min=0, Max=11, Default=0

previousResultMessage     Message string that includes the results of the last run. Default="" Max Length=255

currentStatus             Current status of the update. Values are: 0 (Ready), 1 (Update Pending), 2 (Preparing Image), 3 (Starting VM), 4 (Update In Progress), 5 (Stopping VM), 6 (Submitting Image), 7 (Reverting Image), 8 (Invalid), 9 (Aborted), 10 (Completed Successfully), 11 (No Updates) Min=0, Max=11, Default=0

currentStatusMessage      Message string that includes the results of the run. Default="" Max Length=255

records                     If successful, records retrieved.

### ExecuteGet DiskVersion

Get the fields for a Disk Version or all Disk Versions for a Disk Locator.

parameters                  Parameters needed for the Get.

This required

diskLocatorId             GUID of the Disk Locator to Get Disk Versions of.

or this required & resolution

diskLocatorName           Name of the Disk Locator to Get Disk Versions of.

One of these optional

version                   Specific Version to Get.

type                  nbsp;    When set to 1, get the Maintenance or MaintenanceHighestVersion access version if it exists. When set to 2, get the Test access versions if any exist. When set to 3, get the Override access version if it exists.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

version                   Read-only version number. The base disk is version 0, the other version numbers are in part of the file name. Default=0

fields                      List of fields to retrieve, if not included, all fields are retrieved.

version                   Read-only version number. The base disk is version 0, the other version numbers are in part of the file name. Default=0

description               User description. Default="" Max Length=250

type                      Read-only type of the Disk Version. Values are: 0 (Base), 1 (Manual), 2 (Automatic), 3 (Merge), and 4 (MergeBase) Min=0, Max=4, Default=0

createDate                Read-only Date/Time that the Disk Version was created. Default=getdate

scheduledDate             Date/Time that the Disk Version is scheduled to become available. Format is: YYYY-MM-DD HH:MM. When empty, the disk version is made available immediately. Default=null

deleteWhenFree            Read-only 1 if the Disk Version is no longer needed because of a merge. If not current booted by a Device, it can be deleted. Default=0

access                    Read-only access of the Disk Version. Values are: 0 (Production), 1 (Maintenance), 2 (MaintenanceHighestVersion), 3 (Override), 4 (Merge), 5 (MergeMaintenance), 6 (MergeTest), and 7 (Test) Min=0, Max=7, Default=0

diskFileName              Name of the Disk File including the extension. Default=null

deviceCount               Read-only count of Devices. Default=0

goodInventoryStatus       1 when the up to date file is accessible by all Servers, 0 otherwise. Default=0

taskId                    When a Merge is occurring, this will be set with the task number of the process that is occurring. Default=null

canDelete                 Read-only 1 when the version can be deleted. Default=0

canMerge                  Read-only 1 when the version can be update merged. Will be set for the highest version number. Default=0

canMergeBase              Read-only 1 when the version can be base merged. Will be set for the highest version number. Default=0

canPromote                Read-only 1 when the version can be promoted. Default=0

canRevertTest             Read-only 1 when the version can be reverted to Test Access. Default=0

canRevertMaintenance      Read-only 1 when the version can be reverted to Maintenance Access. Default=0

canSetScheduledDate       Read-only 1 when the version can have the scheduled date modified. Default=0

canOverride               Read-only 1 when the version can be set as the Override. Default=0

isPending                 Read-only 1 when the version scheduledDate has not occurred. Default=0

temporaryVersionSet       Read-only 1 when temporary version(s) are set. Some changes cannot be made to the version when this is set. Default=0

records                     If successful, records retrieved.

### ExecuteGet ExceptionDescriptions

Return all of the exceptions with description.

parameters                  Parameters needed for the Get.

Optional

Culture                   Optional culture to use for the exception descriptions returned.

records                     If successful, records retrieved.

### ExecuteGet Farm

Get the fields for the Farm.

parameters                  Parameters needed for the Get.

Optional

farmId                    GUID of the Farm to Get. This is optional since there is only one Farm.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

farmId                    Read-only GUID that uniquely identifies this Farm. Length=36

farmName                  Name of the Farm. Default="" Max Length=50

description               User description. Default="" Max Length=250

autoAddEnabled            1 when Auto Add is enabled, 0 otherwise. Default=0

auditingEnabled           1 when Auditing is enabled, 0 otherwise. Default=0

lastAuditArchiveDate      Last date of Audit Trail data that was Archived. Format is yyyy/mm/dd Default=null

defaultSiteId             GUID of the Site to place new Devices into automatically. Not used with defaultSiteName. Default=null Length=36

defaultSiteName           Name of the Site to place new Devices into automatically. Not used with defaultSiteId. Default=null

offlineDatabaseSupportEnabled  1 when Offline Database Support is enabled, 0 otherwise. Default=0

adGroupsEnabled           Active Directory groups are used for authorization, when set to 1. Windows groups are used when set to 0. Default=0

licenseServer             License server name. Default="" Max Length=255

licenseServerPort         License server port. Min=1025, Max=65534, Default=27000

licenseTradeUp            License server trade up, when set to 1. Default=0

licenseSKU                licenseSKU. 0 for on-premises, 1 for cloud. Min=0, Max=1, Default=0

automaticMergeEnabled     1 when Automatic Merge is enabled, 0 otherwise. If the number of versions becomes more than the maxVersions value, a merge will occur at the end of PromoteDiskVersion. Default=1

maxVersions               Maximum number a versions of a Disk that can exist before a merge will automatically occur. Min=3, Max=50, Default=5

mergeMode                 Mode to place the version in after a merge has occurred. Values are: 0 (Production), 1 (Test) and 2 (Maintenance). Min=0, Max=2, Default=2

databaseServerName        Read-only name of the database server.

databaseInstanceName      Read-only name of the database instance.

databaseName              Read-only name of the database.

failoverPartnerServerName  Read-only name of the database server.

failoverPartnerInstanceName  Read-only name of the database server instance.

multiSubnetFailover       Read-only Database MultiSubnetFailover value

role                      Read-only Role of the user for this item. 100 is Farm Administrator, and 999 is read-only. Default=999

records                     If successful, records retrieved.

### ExecuteGet FarmView

Get the fields for a Farm View or all Farm Views in the Farm. All Farm Views are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

farmViewId                GUID of the Farm View to Get.

farmViewName              Name of the Farm View to Get.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

farmViewName              name of the Farm View. Max Length=50

description               User description. Default="" Max Length=250

deviceCount               Read-only count of Devices in this Farm View. Default=0

activeDeviceCount         Read-only count of active Devices in this Farm View. Default=0

fields                      List of fields to retrieve, if not included, all fields are retrieved.

farmViewId                Read-only GUID that uniquely identifies this Farm View. Length=36

farmViewName              name of the Farm View. Max Length=50

description               User description. Default="" Max Length=250

deviceCount               Read-only count of Devices in this Farm View. Default=0

activeDeviceCount         Read-only count of active Devices in this Farm View. Default=0

makActivateNeededCount    Read-only count of active Devices that need MAK activation in this Farm View. Default=0

records                     If successful, records retrieved.

### ExecuteGet Groups

Get all of the available groups.

parameters                  Parameters needed for the Get.

This optional

name                      Name of the Group(s) to retrieve. Wildcards are allowed when searching for Active Directory groups. For example, "user\*" will return YOUR\_DOMAIN/BUILTIN/Users, and "\*" will return all the Active Directory groups available.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

name                      Name of the Group.

records                     If successful, records retrieved.

### ExecuteGet NewVersionDisks

Get new Disk versions for the Store on the Server specified.

parameters                  Parameters needed for the Get.

One of these required

serverId                  GUID of the Server to look for new Disk versions.

serverName                Name of the Server to look for new Disk versions.

One of these required

storeId                   GUID of the Store that the Server services to look for new Disk versions.

storeName                 Name of the Store that the Server services to look for new Disk versions.

Optional

autoAddEnabled            1 when undefined Disk versions found should be automatically added, 0 otherwise. Default=0

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

name                      Name of the disk file without the extension.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

name                      Name of the disk file without the extension.

status                    Status of the disk file. Values are: 0 (Valid), 1 (Missing Properties File), 2 (Access Denied), 3 (Access Denied and Missing Properties File), 4 (Invalid Disk File), 5 (Manifest Invalid)

records                     If successful, records retrieved.

### ExecuteGet Server

Get the fields for a Server, all Servers in a Site that use a Store, service a DiskLocator, or for the whole Farm. All Servers are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

serverId                  GUID of the Server to Get.

serverName                Name of the Server to Get.

siteId                    GUID of the Site to Get all Servers.

siteName                  Name of the Site to Get all Servers.

diskLocatorId             GUID of the Disk Locator to Get all Servers.

or this optional & resolution

diskLocatorName           Name of the Disk Locator File to Get all Servers.

One of these optional & resolutions

storeId                   GUID of the Store to Get all Servers.

storeName                 Name of the Store to Get all Servers.

Optional

all                       Set to 1 with storeId or storeName to Get all Servers for the Store including ones with invalid paths.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

serverName                Computer name with no spaces. ASCII computer name characters Max Length=21

description               User description. Default="" Max Length=250

adMaxPasswordAge          Number of days before a password expires. Min=1, Max=30, Default=7

licenseTimeout            Amount of seconds before a license times out. Min=15, Max=300, Default=30

vDiskCreatePacing         VDisk create time pacing in milliseconds. Min=0, Max=5, Default=0

firstPort                 Number of the first UDP port for use by the Stream Service, First and Last must allow at least 5 ports. Min=1025, Max=65534, Default=6910

lastPort                  Number of the last UDP port for use by the Stream Service, First and Last must allow at least 5 ports. Min=1025, Max=65534, Default=6930

threadsPerPort            Number of worker threads per IO port. Required that (threadPerPort \* numberPorts \* numberIPs) <= 1000. Min=1, Max=60, Default=8

buffersPerThread          Number of buffers per worker thread. Min=1, Max=128, Default=24

serverCacheTimeout        Number of seconds to wait before considering another Server is down. Min=5, Max=60, Default=8

ioBurstSize               Number of bytes read/writes can send in a burst of packets. Required that ioBurstSize/(maxTransmissionUnits-76)<=32. Min=4096, Max=61440, Default=32768

maxTransmissionUnits      Ethernet maximum transmission unit size for the protocol for use for Server and Device. Required that ioBurstSize/(maxTransmissionUnits-76)<=32. Min=502, Max=16426, Default=1506

maxBootDevicesAllowed     Maximum number of Devices allowed to boot simultaneously. Min=1, Max=1000, Default=500

maxBootSeconds            Maximum number of seconds for a Device to boot. Min=10, Max=900, Default=60

bootPauseSeconds          Number of seconds that a Device will pause during login if its server busy. Min=1, Max=60, Default=10

adMaxPasswordAgeEnabled   Age the password, when set to 1. Default=0

fields                      List of fields to retrieve, if not included, all fields are retrieved.

serverId                  Read-only GUID that uniquely identifies this Server. Length=36

serverName                Computer name with no spaces. ASCII computer name characters Max Length=21

siteId                    GUID of the Site this Server is to be a member of. It is not used with siteName. Length=36

siteName                  Name of the Site this Server is to be a member of. It is not used with siteId.

description               User description. Default="" Max Length=250

adMaxPasswordAge          Number of days before a password expires. Min=1, Max=30, Default=7

licenseTimeout            Amount of seconds before a license times out. Min=15, Max=300, Default=30

vDiskCreatePacing         VDisk create time pacing in milliseconds. Min=0, Max=5, Default=0

firstPort                 Number of the first UDP port for use by the Stream Service, First and Last must allow at least 5 ports. Min=1025, Max=65534, Default=6910

lastPort                  Number of the last UDP port for use by the Stream Service, First and Last must allow at least 5 ports. Min=1025, Max=65534, Default=6930

threadsPerPort            Number of worker threads per IO port. Required that (threadPerPort \* numberPorts \* numberIPs) <= 1000. Min=1, Max=60, Default=8

buffersPerThread          Number of buffers per worker thread. Min=1, Max=128, Default=24

serverCacheTimeout        Number of seconds to wait before considering another Server is down. Min=5, Max=60, Default=8

ioBurstSize               Number of bytes read/writes can send in a burst of packets. Required that ioBurstSize/(maxTransmissionUnits-76)<=32. Min=4096, Max=61440, Default=32768

maxTransmissionUnits      Ethernet maximum transmission unit size for the protocol for use for Server and Device. Required that ioBurstSize/(maxTransmissionUnits-76)<=32. Min=502, Max=16426, Default=1506

maxBootDevicesAllowed     Maximum number of Devices allowed to boot simultaneously. Min=1, Max=1000, Default=500

maxBootSeconds            Maximum number of seconds for a Device to boot. Min=10, Max=900, Default=60

bootPauseSeconds          Number of seconds that a Device will pause during login if its server busy. Min=1, Max=60, Default=10

adMaxPasswordAgeEnabled   Age the password, when set to 1. Default=0

eventLoggingEnabled       Enable event logging, when set to 1. Default=0

nonBlockingIoEnabled      Use non-Blocking IO, when set to 1. Default=1

role                      Read-only Role of the user for this item. 100 is Farm Administrator, and 200 is Site Administrator. Default=999

ip                        One or more streaming ip addresses. If more than one ip is included, the ip addresses are comma delimited.

initialQueryConnectionPoolSize  Initial size of database connection pool for non-transactional queries. Min=1, Max=1000, Default=50

initialTransactionConnectionPoolSize  Initial size of database connection pool for transactional queries. Min=1, Max=1000, Default=50

maxQueryConnectionPoolSize  Maximum size of database connection pool for non-transactional queries. Min=1, Max=32767, Default=1000

maxTransactionConnectionPoolSize  Maximum size of database connection pool for transactional queries. Min=1, Max=32767, Default=1000

refreshInterval           Interval, in number of seconds, the server should wait before refreshing settings. If set to 0, unused database connections are never released. Min=0, Max=32767, Default=300

unusedDbConnectionTimeout  Interval, in number of seconds, a connection should go unused before it is to be released. Min=0, Max=32767, Default=300

busyDbConnectionRetryCount  Number of times a failed database connection will be retried. Min=0, Max=32767, Default=2

busyDbConnectionRetryInterval  Interval, in number of milliseconds, the server should wait before retrying to connect to a database. Min=0, Max=10000, Default=25

localConcurrentIoLimit    Maximum concurrent IO transactions it performs for vDisks that are local. A value of 0 disables the feature. Min=0, Max=128, Default=4

remoteConcurrentIoLimit   Maximum concurrent IO transactions it performs for vDisks that are remote. A value of 0 disables the feature. Min=0, Max=128, Default=4

active                    1 if the Server is currently active, 2 if unknown, and 0 otherwise. Min=0, Max=2, Default=0

logLevel                  Level to perform logging at. Values are: 0 (None), 1 (Fatal), 2 (Error), 3 (Warning), 4 (Info), 5 (Debug), and 6 (Trace). Min=0, Max=6, Default=4

logFileSizeMax            Maximum size log files can reach in Megabytes. Min=1, Max=50, Default=5

logFileBackupCopiesMax    Maximum number of log file backups. Min=1, Max=50, Default=4

powerRating               A strictly relative rating of this Server's capabilities when compared to other Servers in the Store(s) it belongs too; can be used to help tune load balancing. Min=0.1, Max=1000, Default=1

serverFqdn                Read-only fully qualified domain name. Default=null Max Length=1024

managementIp              IP address used for management communications between Servers. Default=0.0.0.0

lastCeipUploadAttempt     Time that this server last attempted a CEIP upload. Default=null

lastBugReportAttempt      Time that this server last attempted to upload or generate a bug report bundle. Default=null

lastBugReportStatus       Status of the last bug report on this server. Default=null Max Length=250

lastBugReportResult       Status of the last bug report on this server. Default=null Max Length=4000

lastBugReportSummary      Summary of the last bug report on this server. Default=null Max Length=250

records                     If successful, records retrieved.

### ExecuteGet ServerBiosBootstrap

Oem Only: Get the bootstrap fields for the Server dell\_bios.bin BIOS bootstrap file.

parameters                  Parameters needed for the Get.

One of these required

serverId                  GUID of the Server to Get the dell\_bios.bin BIOS bootstrap file from.

serverName                Name of the Server to Get the dell\_bios.bin BIOS bootstrap file from.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

enabled                   Automatically update the BIOS on the target device with these setting when set to 1, otherwise do not use these settings. Default=0

dhcpEnabled               Use DHCP to retrieve target device IP when set to 1, otherwise use the static domain, dnsIpAddress1 and dnsIpAddress2 settings. Default=1

lookup                    Use DNS to find the Server when set to 1 with the serverName host value, otherwise use the bootserver1\_Ip, bootserver1\_Port, bootserver2\_Ip, bootserver2\_Port, bootserver3\_Ip, bootserver3\_Port, bootserver4\_Ip, and bootserver4\_Port settings. Default=1

verboseMode               Display verbose diagnostic information when set to 1. Default=0

interruptSafeMode         Interrupt safe mode (use if target device hangs during boot) when set to 1. Default=0

paeMode                   PAE mode (use if PAE enabled in boot.ini of target device) when set to 1. Default=0

bootFromHdOnFail          For network recovery reboot to hard drive when set to 1, restore network connection when set to 0. Default=0

recoveryTime              When bootFromHdOnFail is 1, this is the number of seconds to wait before reboot to hard drive. Min=10, Max=60000, Default=50

pollingTimeout            Login polling timeout in milliseconds. Min=1000, Max=60000, Default=5000

generalTimeout            Login general timeout in milliseconds. Min=1000, Max=60000, Default=5000

serverName                Host to use for DNS lookup. Only used when lookup is 1. Default=IMAGESERVER1

bootserver1\_Ip            1st boot server IP. Only used when lookup is 0.

bootserver1\_Port          1st boot server port. Only used when lookup is 0. Min=1025, Max=65536, Default=6910

bootserver2\_Ip            2nd boot server IP. Only used when lookup is 0. Default=0.0.0.0

bootserver2\_Port          2nd boot server port. Only used when lookup is 0. Min=1025, Max=65536, Default=6910

bootserver3\_Ip            3rd boot server IP. Only used when lookup is 0. Default=0.0.0.0

bootserver3\_Port          3rd boot server port. Only used when lookup is 0. Min=1025, Max=65536, Default=6910

bootserver4\_Ip            4th boot server IP. Only used when lookup is 0. Default=0.0.0.0

bootserver4\_Port          4th boot server port. Only used when lookup is 0. Min=1025, Max=65536, Default=6910

domain                    Domain of the primary and secondary DNS servers. Only used when dhcpEnabled is 0.

dnsIpAddress1             Primary DNS server IP. Only used when dhcpEnabled is 0.

dnsIpAddress2             Secondary DNS server IP. Only used when dhcpEnabled is 0.

records                     If successful, records retrieved.

### ExecuteGet ServerBootstrap

Get the bootstrap fields for the Server and named bootstrap file specified.

parameters                  Parameters needed for the Get.

One of these required

serverId                  GUID of the Server to Get the named bootstrap file from.

serverName                Name of the Server to Get the named bootstrap file from.

This required

name                      Name of the bootstrap file.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

bootserver1\_Ip            1st boot server IP.

bootserver1\_Netmask       1st boot server netmask. Default=0.0.0.0

bootserver1\_Gateway       1st boot server gateway. Default=0.0.0.0

bootserver1\_Port          1st boot server port. Min=1025, Max=65536, Default=6910

bootserver2\_Ip            2nd boot server IP. Default=0.0.0.0

bootserver2\_Netmask       2nd boot server netmask. Default=0.0.0.0

bootserver2\_Gateway       2nd boot server gateway. Default=0.0.0.0

bootserver2\_Port          2nd boot server port. Min=1025, Max=65536, Default=6910

bootserver3\_Ip            3rd boot server IP. Default=0.0.0.0

bootserver3\_Netmask       3rd boot server netmask. Default=0.0.0.0

bootserver3\_Gateway       3rd boot server gateway. Default=0.0.0.0

bootserver3\_Port          3rd boot server port. Min=1025, Max=65536, Default=6910

bootserver4\_Ip            4th boot server IP. Default=0.0.0.0

bootserver4\_Netmask       4th boot server netmask. Default=0.0.0.0

bootserver4\_Gateway       4th boot server gateway. Default=0.0.0.0

bootserver4\_Port          4th boot server port. Min=1025, Max=65536, Default=6910

verboseMode               Display verbose diagnostic information when set to 1. Default=0

interruptSafeMode         Interrupt safe mode (use if target device hangs during boot) when set to 1. Default=0

paeMode                   PAE mode (use if PAE enabled in boot.ini of target device) when set to 1. Default=0

bootFromHdOnFail          For network recovery reboot to hard drive when set to 1, restore network connection when set to 0. Default=0

recoveryTime              When bootFromHdOnFail is 1, this is the number of seconds to wait before reboot to hard drive. Min=10, Max=60000, Default=50

pollingTimeout            Login polling timeout in milliseconds. Min=1000, Max=60000, Default=5000

generalTimeout            Login general timeout in milliseconds. Min=1000, Max=60000, Default=5000

records                     If successful, records retrieved.

### ExecuteGet ServerBootstrapNames

Get the bootstrap names for a Server.

parameters                  Parameters needed for the Get.

One of these required

serverId                  GUID of the Server to Get bootstrap names for.

serverName                Name of the Server to Get bootstrap names for.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

name                      Bootstrap file name.

records                     If successful, records retrieved.

### ExecuteGet ServerCustomProperty

Get the Server Custom Property names and values.

parameters                  Parameters needed for the Get.

One of these required

serverId                  GUID of the Server.

serverName                Name of the Server.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

name                      Name of the Server custom property. Max Length=250

fields                      List of fields to retrieve, if not included, all fields are retrieved.

name                      Name of the Server custom property. Max Length=250

value                     Value of the Server custom property. Max Length=1000

records                     If successful, records retrieved.

### ExecuteGet ServerInfo

Get the fields and status for a Server, all Servers in a Site that use a Store, service a DiskLocator, or for the whole Farm. All Servers are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

serverId                  GUID of the Server to Get.

serverName                Name of the Server to Get.

siteId                    GUID of the Site to Get all Servers.

siteName                  Name of the Site to Get all Servers.

diskLocatorId             GUID of the Disk Locator to Get all Servers.

or this optional & resolution

diskLocatorName           Name of the Disk Locator File to Get all Servers.

One of these optional & resolutions

storeId                   GUID of the Store to Get all Servers.

storeName                 Name of the Store to Get all Servers.

Optional

all                       Set to 1 with storeId or storeName to Get all Servers for the Store including ones with invalid paths.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

serverName                Computer name with no spaces. ASCII computer name characters Max Length=21

description               User description. Default="" Max Length=250

adMaxPasswordAge          Number of days before a password expires. Min=1, Max=30, Default=7

licenseTimeout            Amount of seconds before a license times out. Min=15, Max=300, Default=30

vDiskCreatePacing         VDisk create time pacing in milliseconds. Min=0, Max=5, Default=0

firstPort                 Number of the first UDP port for use by the Stream Service, First and Last must allow at least 5 ports. Min=1025, Max=65534, Default=6910

lastPort                  Number of the last UDP port for use by the Stream Service, First and Last must allow at least 5 ports. Min=1025, Max=65534, Default=6930

threadsPerPort            Number of worker threads per IO port. Required that (threadPerPort \* numberPorts \* numberIPs) <= 1000. Min=1, Max=60, Default=8

buffersPerThread          Number of buffers per worker thread. Min=1, Max=128, Default=24

serverCacheTimeout        Number of seconds to wait before considering another Server is down. Min=5, Max=60, Default=8

ioBurstSize               Number of bytes read/writes can send in a burst of packets. Required that ioBurstSize/(maxTransmissionUnits-76)<=32. Min=4096, Max=61440, Default=32768

maxTransmissionUnits      Ethernet maximum transmission unit size for the protocol for use for Server and Device. Required that ioBurstSize/(maxTransmissionUnits-76)<=32. Min=502, Max=16426, Default=1506

maxBootDevicesAllowed     Maximum number of Devices allowed to boot simultaneously. Min=1, Max=1000, Default=500

maxBootSeconds            Maximum number of seconds for a Device to boot. Min=10, Max=900, Default=60

bootPauseSeconds          Number of seconds that a Device will pause during login if its server busy. Min=1, Max=60, Default=10

adMaxPasswordAgeEnabled   Age the password, when set to 1. Default=0

fields                      List of fields to retrieve, if not included, all fields are retrieved.

serverId                  Read-only GUID that uniquely identifies this Server. Length=36

serverName                Computer name with no spaces. ASCII computer name characters Max Length=21

siteId                    GUID of the Site this Server is to be a member of. It is not used with siteName. Length=36

siteName                  Name of the Site this Server is to be a member of. It is not used with siteId.

description               User description. Default="" Max Length=250

adMaxPasswordAge          Number of days before a password expires. Min=1, Max=30, Default=7

licenseTimeout            Amount of seconds before a license times out. Min=15, Max=300, Default=30

vDiskCreatePacing         VDisk create time pacing in milliseconds. Min=0, Max=5, Default=0

firstPort                 Number of the first UDP port for use by the Stream Service, First and Last must allow at least 5 ports. Min=1025, Max=65534, Default=6910

lastPort                  Number of the last UDP port for use by the Stream Service, First and Last must allow at least 5 ports. Min=1025, Max=65534, Default=6930

threadsPerPort            Number of worker threads per IO port. Required that (threadPerPort \* numberPorts \* numberIPs) <= 1000. Min=1, Max=60, Default=8

buffersPerThread          Number of buffers per worker thread. Min=1, Max=128, Default=24

serverCacheTimeout        Number of seconds to wait before considering another Server is down. Min=5, Max=60, Default=8

ioBurstSize               Number of bytes read/writes can send in a burst of packets. Required that ioBurstSize/(maxTransmissionUnits-76)<=32. Min=4096, Max=61440, Default=32768

maxTransmissionUnits      Ethernet maximum transmission unit size for the protocol for use for Server and Device. Required that ioBurstSize/(maxTransmissionUnits-76)<=32. Min=502, Max=16426, Default=1506

maxBootDevicesAllowed     Maximum number of Devices allowed to boot simultaneously. Min=1, Max=1000, Default=500

maxBootSeconds            Maximum number of seconds for a Device to boot. Min=10, Max=900, Default=60

bootPauseSeconds          Number of seconds that a Device will pause during login if its server busy. Min=1, Max=60, Default=10

adMaxPasswordAgeEnabled   Age the password, when set to 1. Default=0

eventLoggingEnabled       Enable event logging, when set to 1. Default=0

nonBlockingIoEnabled      Use non-Blocking IO, when set to 1. Default=1

role                      Read-only Role of the user for this item. 100 is Farm Administrator, and 200 is Site Administrator. Default=999

ip                        One or more streaming ip addresses. If more than one ip is included, the ip addresses are comma delimited.

initialQueryConnectionPoolSize  Initial size of database connection pool for non-transactional queries. Min=1, Max=1000, Default=50

initialTransactionConnectionPoolSize  Initial size of database connection pool for transactional queries. Min=1, Max=1000, Default=50

maxQueryConnectionPoolSize  Maximum size of database connection pool for non-transactional queries. Min=1, Max=32767, Default=1000

maxTransactionConnectionPoolSize  Maximum size of database connection pool for transactional queries. Min=1, Max=32767, Default=1000

refreshInterval           Interval, in number of seconds, the server should wait before refreshing settings. If set to 0, unused database connections are never released. Min=0, Max=32767, Default=300

unusedDbConnectionTimeout  Interval, in number of seconds, a connection should go unused before it is to be released. Min=0, Max=32767, Default=300

busyDbConnectionRetryCount  Number of times a failed database connection will be retried. Min=0, Max=32767, Default=2

busyDbConnectionRetryInterval  Interval, in number of milliseconds, the server should wait before retrying to connect to a database. Min=0, Max=10000, Default=25

localConcurrentIoLimit    Maximum concurrent IO transactions it performs for vDisks that are local. A value of 0 disables the feature. Min=0, Max=128, Default=4

remoteConcurrentIoLimit   Maximum concurrent IO transactions it performs for vDisks that are remote. A value of 0 disables the feature. Min=0, Max=128, Default=4

active                    1 if the Server is currently active, 2 if unknown, and 0 otherwise. Min=0, Max=2, Default=0

logLevel                  Level to perform logging at. Values are: 0 (None), 1 (Fatal), 2 (Error), 3 (Warning), 4 (Info), 5 (Debug), and 6 (Trace). Min=0, Max=6, Default=4

logFileSizeMax            Maximum size log files can reach in Megabytes. Min=1, Max=50, Default=5

logFileBackupCopiesMax    Maximum number of log file backups. Min=1, Max=50, Default=4

powerRating               A strictly relative rating of this Server's capabilities when compared to other Servers in the Store(s) it belongs too; can be used to help tune load balancing. Min=0.1, Max=1000, Default=1

serverFqdn                Read-only fully qualified domain name. Default=null Max Length=1024

managementIp              IP address used for management communications between Servers. Default=0.0.0.0

lastCeipUploadAttempt     Time that this server last attempted a CEIP upload. Default=null

lastBugReportAttempt      Time that this server last attempted to upload or generate a bug report bundle. Default=null

lastBugReportStatus       Status of the last bug report on this server. Default=null Max Length=250

lastBugReportResult       Status of the last bug report on this server. Default=null Max Length=4000

lastBugReportSummary      Summary of the last bug report on this server. Default=null Max Length=250

contactIp                 Read-only contact IP for the Server.

contactPort               Read-only contact port for the Server.

deviceCount               Read-only count of Devices. Default=0

records                     If successful, records retrieved.

### ExecuteGet ServerStatus

Get the Server Status fields for a Server.

parameters                  Parameters needed for the Get.

One of these required

serverId                  GUID of the Server to Get status for.

serverName                Name of Server to Get status for.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

serverId                  Read-only GUID of the Server. Can be used with Get Server. Length=36

serverName                Read-only Name of the Server. Can be used with Get Server.

ip                        Read-only contact IP for the Server.

port                      Read-only contact port for the Server.

deviceCount               Read-only count of Devices. Default=0

status                    Status of the server, 0 if down, 1 if up and 2 if unknown. Default=0

records                     If successful, records retrieved.

### ExecuteGet ServerStore

Get the directory and cache paths of a Server for one or all Stores.

parameters                  Parameters needed for the Get.

One of these required

serverId                  GUID of a Server.

serverName                Name of a Server.

One of these optional

storeId                   GUID of the Store.

storeName                 Name of the Store.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

storeId                   GUID of the Store. storeName can be used instead. Length=36

storeName                 Name of the Store. storeId can be used instead.

serverId                  GUID of the server that uses the Store. serverName can be used instead. Length=36

serverName                Name of the server that uses the Store. serverId can be used instead.

path                      Directory path that the Server uses to access the Store. Default="" Max Length=255

cachePath                 Cache path(s) that the Server uses with the Store. It is an ordered comma-delimited list. If none are specified the caches will be placed in the Store cachePath. Default=None

records                     If successful, records retrieved.

### ExecuteGet Site

Get the fields for a Site or all Sites. All Sites are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

siteId                    GUID of the Site to Get.

siteName                  Name of the Site to Get.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

siteName                  Name of the Site. Max Length=50

description               User description. Default="" Max Length=250

fields                      List of fields to retrieve, if not included, all fields are retrieved.

siteId                    Read-only GUID that uniquely identifies this Site. Length=36

siteName                  Name of the Site. Max Length=50

description               User description. Default="" Max Length=250

defaultCollectionId       GUID of the Collection to place new Devices into automatically. Not used with defaultCollectionName. Default=null Length=36

defaultCollectionName     Name of the Collection to place new Devices into automatically. Not used with defaultCollectionId. Default=null

inventoryFilePollingInterval  The number of seconds between polls for Disk changes in the Stores. Min=1, Max=600, Default=60

enableDiskUpdate          1 when Disk Updated is enabled for the Site, 0 otherwise. Default=0

diskUpdateServerId        GUID of the Disk Update Server for the Site. Not used with diskUpdateServerName. Default=null Length=36

diskUpdateServerName      Name of the Disk Update Server for the Site. Not used with diskUpdateServerId. Default=null

makUser                   User name used for MAK activation. Default=null Max Length=64

makPassword               User password used for MAK activation. Default=null Max Length=64

role                      Read-only Role of the user for this item. 100 is Farm Administrator, 200 is Site Administrator, and 999 is read-only. Default=999

records                     If successful, records retrieved.

### ExecuteGet SiteView

Get the fields for a Site View or all Site Views in a Site or the whole Farm. All Site Views are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

siteViewId                GUID of the Site View to Get.

siteId                    GUID of the Site to Get all Views for.

siteName                  Name of the Site to Get all Views for.

or this optional & resolution

siteViewName              Name of the Site View to Get.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

siteViewName              Name of the Site View. Max Length=50

description               User description. Default="" Max Length=250

deviceCount               Read-only count of Devices in this Site View. Default=0

deviceWithPVDCount        Read-only count of Devices with Personal vDisk in this Site View. Default=0

activeDeviceCount         Read-only count of active Devices in this Site View. Default=0

fields                      List of fields to retrieve, if not included, all fields are retrieved.

siteViewId                Read-only GUID that uniquely identifies this Site View. Length=36

siteViewName              Name of the Site View. Max Length=50

siteId                    GUID of the Site this View is to be a member of. It is not used with siteName. Length=36

siteName                  Name of the Site this View is to be a member of. It is not used with siteId.

description               User description. Default="" Max Length=250

deviceCount               Read-only count of Devices in this Site View. Default=0

deviceWithPVDCount        Read-only count of Devices with Personal vDisk in this Site View. Default=0

activeDeviceCount         Read-only count of active Devices in this Site View. Default=0

makActivateNeededCount    Read-only count of active Devices that need MAK activation in this Site View. Default=0

role                      Read-only Role of the user for this item. 100 is Farm Administrator, and 200 is Site Administrator. Default=999

records                     If successful, records retrieved.

### ExecuteGet Store

Get the fields for a Store or all Stores for a Server, Site or the Farm. All Stores are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

storeId                   GUID of the Store to Get.

storeName                 Name of the Store to Get.

serverId                  GUID of the Server to Get all Stores for.

serverName                Name of the Server to Get all Stores for.

siteId                    GUID of the Site to Get all Stores for.

siteName                  Name of the Site to Get all Stores for.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

storeName                 Name of the Store. Max Length=50

description               User description. Default="" Max Length=250

fields                      List of fields to retrieve, if not included, all fields are retrieved.

storeId                   Read-only GUID that uniquely identifies this Store. Length=36

storeName                 Name of the Store. Max Length=50

siteId                    GUID of the Site where Administrators of that Site can change this Store. Not used for Farm Stores. siteName can be used instead. Default=null Length=36

siteName                  Name of the Site where Administrators of that Site can change this Store. Not used for Farm Stores. siteId can be used instead. Default=null

description               User description. Default="" Max Length=250

path                      Default directory path that the Servers use to access this Store. Max Length=255

cachePath                 Default Cache path(s) that the Servers use with this Store. It is an ordered comma-delimited list. If none are specified the caches will be placed in the WriteCache subdirectory of the Store path. Default=None

role                      Read-only Role of the user for this item. 100 is Farm Administrator, 200 is Site Administrator, and 999 is read-only. Default=999

pathType                  Read-only field indicating if the vdisks are on a server's local hard disk or on a remote share.

records                     If successful, records retrieved.

### ExecuteGet StoreSharedOrServerPath

Get the Stores and paths for the serverName specified or Stores with only shared UNC paths.

parameters                  Parameters needed for the Get.

One of these required

siteId                    GUID of a Site used for authorization check.

siteName                  Name of a Site used for authorization check.

Optional

serverName                Name of a Server to also get local Store paths for.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

storeName                 Name of the Store.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

storeId                   GUID of the Store.

storeName                 Name of the Store.

path                      Directory path that the Servers use to access this Store.

records                     If successful, records retrieved.

### ExecuteGet Task

Get the current Task fields for select, or all active and completed un-cleared tasks.

parameters                  Parameters needed for the Get.

One of these optional

taskId                    ID of the Task to get.

siteId                    GUID of the Site to get Tasks for.

siteName                  Name of the Site to get Tasks for.

Optional

state                     The TaskState to get Tasks for. Values are: 0 (Processing), 1 (Cancelled), and 2 (Complete).

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

taskId                    Unique ID of the task.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

taskId                    Unique ID of the task.

siteId                    GUID of the Site that this Task is being processed in. Default=null Length=36

siteName                  Name of the Site that that this Task is being processed in.

handle                    Handle to a running function.

serverFqdn                Qualified name of the server. Default=null Max Length=1024

ip                        IP Address of the remote host.

port                      Port number of the remote service.

startTime                 Time the task was started. Format is: YYYY-MM-DD HH:MM:SS.

expirationTime            Time the task record may be removed from the database if the task does not complete. Format is: YYYY-MM-DD HH:MM:SS.

state                     State of the Task. Values are: 0 (Processing), 1 (Cancelled), and 2 (Complete). Min=0, Max=2

commandType               Type of the command. Values are: Add, Delete, Get, Info, Run, RunWithReturn, Set and SetList. Default="" Max Length=13

command                   Command being processed. Default="" Max Length=50

mapiException             Exception result in XML format. Default=null

results                   Result in XML format. Default=null

records                     If successful, records retrieved.

### ExecuteGet UndefinedDisks

Get undefined Disks for the Store on the Server specified.

parameters                  Parameters needed for the Get.

One of these required

serverId                  GUID of the Server to look for undefined Disks.

serverName                Name of the Server to look for undefined Disks.

One of these required

storeId                   GUID of the Store that the Server services to look for undefined Disks.

storeName                 Name of the Store that the Server services to look for undefined Disks.

Optional

autoAddEnabled            1 when undefined Disks found should be automatically added, 0 otherwise. Default=0

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

name                      Name of the disk file without the extension.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

name                      Name of the disk file without the extension.

status                    Status of the disk file. Values are: 0 (Valid), 1 (Missing Properties File), 2 (Access Denied), 3 (Access Denied and Missing Properties File), 4 (Invalid Disk File), 5 (Manifest Missing or Invalid), 6 (Both VHD and VHDX)

format                    Format of the image. Values are: 0 (VHD), 1 (VHDX). Default=0

records                     If successful, records retrieved.

### ExecuteGet UpdateTask

Get the fields for an Update Task or all Update Tasks in a Site or the whole Farm. All Update Tasks are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

updateTaskId              GUID of the Update Task to Get.

siteId                    GUID of the Site to Get all Update Tasks for.

siteName                  Name of the Site to Get all Update Tasks for.

or this optional & resolution

updateTaskName            Name of the Update Task to Get.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

updateTaskName            Name of the Update Task. It is unique within the Site. Max Length=50

description               User description. Default="" Max Length=250

fields                      List of fields to retrieve, if not included, all fields are retrieved.

updateTaskId              Read-only GUID that uniquely identifies this Update Task. Length=36

updateTaskName            Name of the Update Task. It is unique within the Site. Max Length=50

siteId                    GUID of the Site that this Update Task is a member of. It is not used with siteName. Length=36

siteName                  Name of the Site that this Update Task is a member of. It is not used with siteId.

description               User description. Default="" Max Length=250

enabled                   1 when it will be processed, 0 otherwise. Default=1

hour                      The hour of the day to perform the task. Min=0, Max=23, Default=0

minute                    The minute of the hour to perform the task. Min=0, Max=59, Default=0

recurrence                The update will reoccur on this schedule. 0 = None, 1 = Daily, 2 = Every Weekday, 3 = Weekly, 4 = Monthly Date, 5 = Monthly Type. Min=0, Max=5, Default=0

dayMask                   Days selected values. 1 = Monday, 2 = Tuesday, 4 = Wednesday, 8 = Thursday, 16 = Friday, 32 = Saturday, 64 = Sunday, 128 = Day. Default=0. This is used with Weekly and Monthly Type recurrence. Min=1, Max=255, Default=4

date                      Comma delimited days of the month. Numbers from 1-31 are the only valid values. This is used with Monthly Date recurrence. Default="" Max Length=83

monthlyOffset             When to happen monthly. 0 = None, 1 = First, 2 = Second, 3 = Third, 4 = Forth, 5 = Last. This is used with Monthly Type recurrence. Min=0, Max=5, Default=3

esdType                   Esd to use. Valid values are SCCM or WSUS. If no value, a custom script is run on the client. Default=null Max Length=50

preUpdateScript           Script file to run before the update starts. Default=null Max Length=255

preVmScript               Script file to run before the VM is loaded. Default=null Max Length=255

postUpdateScript          Script file to run after the update finishes. Default=null Max Length=255

postVmScript              Script file to run after the VM is unloaded. Default=null Max Length=255

domain                    Domain to add the Disk Update Device(s) to. If not included, the first Domain Controller found on the Server is used. Default=null Max Length=255

organizationUnit          Organizational Unit to add the Disk Update Device(s) to. This parameter is optional. If it is not specified, the device is added to the built in Computers container. Child OU's should be delimited with forward slashes, e.g. "ParentOU/ChildOU". Special characters in an OU name, such as '"', '#', '+', ',', ';', '>', '=', must be escaped with a backslash. For example, an OU called "commaIn,TheMiddle" must be specified as "commaIn\\,TheMiddle". The old syntax of delimiting child OU's with a comma is still supported, but deprecated. Note that in this case, the child OU comes first, e.g. "ChildOU,ParentOU". Default=null Max Length=255

postUpdateApprove         Access to place the version in after the update has occurred. 0 = Production, 1 = Test, 2 = Maintenance. Min=0, Max=2, Default=0

records                     If successful, records retrieved.

### ExecuteGet VirtualHostingPool

Get the fields for a Virtual Hosting Pool or all Virtual Hosting Pools in a Site or the whole Farm. All Virtual Hosting Pools are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

One of these optional

virtualHostingPoolId      GUID of the Virtual Hosting Pool to Get.

siteId                    GUID of the Site to Get all Virtual Hosting Pools for.

siteName                  Name of the Site to Get all Virtual Hosting Pools for.

or this optional & resolution

virtualHostingPoolName    Name of the Virtual Hosting Pool to Get.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

sortField                   Name of field to sort on. If not included, the first field listed is used. Set ascending to true for ascending order, or false for descending order.

virtualHostingPoolName    Name of the Virtual Hosting Pool. It is unique within the Site. Max Length=50

description               User description. Default="" Max Length=250

fields                      List of fields to retrieve, if not included, all fields are retrieved.

virtualHostingPoolId      Read-only GUID that uniquely identifies this Virtual Hosting Pool. Length=36

virtualHostingPoolName    Name of the Virtual Hosting Pool. It is unique within the Site. Max Length=50

siteId                    GUID of the Site that this Virtual Hosting Pool is a member of. It is not used with siteName. Length=36

siteName                  Name of the Site that this Virtual Hosting Pool is a member of. It is not used with siteId.

type                      Type of the Virtual Hosting Pool. 0 = Citrix XenServer, 1 = Microsoft SCVMM/Hyper-V, 2 = VMWare vSphere/ESX. Min=0, Max=3, Default=0

description               User description. Default="" Max Length=250

server                    Name or IP of the Host Server. Max Length=255

port                      Port of the Host Server. Min=80, Max=65534, Default=80

datacenter                Datacenter of the Virtual Hosting Pool. Default="" Max Length=250

updateLimit               Number of updates at the same time. Min=2, Max=1000, Default=1000

updateTimeout             Timeout for updates. Min=2, Max=240, Default=60

shutdownTimeout           Timeout for shutdown. Min=2, Max=30, Default=10

userName                  Name to use when logging into the Server.

password                  Password to use when logging into the Server.

xdHostingUnitUuid         UUID of XenDesktop Hosting Unit Default=null Length=36

prepopulateEnabled        Enable prepopulate when set to 1 Default=0

xsPvsSiteUuid             UUID of XenServer PVS\_site  Default=null Length=36

platformVersion            Hypervisor Host Version  Default=null Max Length=250

xdHcHypervisorConnectionName  Hypervisor Connection Name for HCL Connection Details object Default=null Max Length=250

xdHcHypervisorConnectionUid  Hypervisor Connection Uid for HCL Connection Details object Default=null Max Length=250

xdHcRevision              Revision for HCL Connection Details object Default=null Max Length=250

xdHcCustomProperties      Custom Properties for HCL Connection Details object Default=null Max Length=250

xdHcSslThumbprints        Ssl Thumbprints for HCL Connection Details object Default=null Max Length=250

records                     If successful, records retrieved.

### ExecuteGet VirtualHostingPoolServer

parameters                  Parameters needed for the Get.

Optional

virtualHostingPoolId      GUID of the Virtual Hosting Pool to Get.

serverId                  GUID of the Server to Get.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

virtualHostingPoolId      GUID of the Virtual Hosting Pool being used for XenServer PVS proxy. Length=36

serverId                  GUID of the Server that has a PVS\_server in XenServer Length=36

xsPvsServerUuid           UUID of the XenServer PVS\_server Length=36

records                     If successful, records retrieved.

### ExecuteGet XDSite

Get the fields for a XenDesktop Site or all XenDesktop Sites. All XenDisktop Sites are returned if no parameters are passed.

parameters                  Parameters needed for the Get.

This optional

xdSiteId                  GUID of the XenDesktop Site to Get.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

xdSiteId                  GUID of the XenDesktop Site. Length=36

configServices            Comma delimited list of XenDesktop Server addresses. Max Length=2000

records                     If successful, records retrieved.

## ExecuteInfo

MapiReturn ExecuteInfo(string command,

List<KeyValuePair<string, string>> parameters,

List<string> fields,

out List<List<KeyValuePair<string, string>>> records);

### ExecuteInfo Group

Get the fields for the Groups for the user or the System.

parameters                  Parameters needed for the Info request.

Optional

domain                    Domain of user (may be the name of the local computer).

user                      Name of user.

adGroupsEnabled           Get Active Directory groups, when set to 1. Get Windows groups, when set to 0. If not included, the Farm adGroupsEnabled setting is used.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

name                      Name of the Group.

guid                      GUID of the Active Directory group. It will be null for Windows groups.

records                     If successful, records retrieved.

### ExecuteInfo LocalServer

Return one record with the local server's NetBios name

fields                      List of fields to retrieve, if not included, all fields are retrieved.

LocalServer               NetBios name of local server.

records                     If successful, records retrieved.

### ExecuteInfo MapiErrorCode

Return the string and numeric versions of each Mapi error code.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

mapiVersion               Version of the system in major.minor.point.build format.

dbVersion                 Version of the database schema as a number. Default=0

type                      Type of system. Values are 0 (Normal), 1 (OROM), and 2 (Secure). Default=0

dbEdition                 Edition of the database. If 'Express Edition', monitor dbSize.

dbSize                    Size of the database in MB. Monitor this value if the edition is 'Express Edition' and this value is close to reaching the 4000 MB maximum. Default=0

mapiVersionNumber         Internal version number of the system. It is a number that is increaed by 100 for each major and minor release. Point releases are the numbers between each 100. Default=0

records                     If successful, records retrieved.

### ExecuteInfo Version

Return one record with the version information.

fields                      List of fields to retrieve, if not included, all fields are retrieved.

mapiVersion               Version of the system in major.minor.point.build format.

dbVersion                 Version of the database schema as a number. Default=0

type                      Type of system. Values are 0 (Normal), 1 (OROM), and 2 (Secure). Default=0

dbEdition                 Edition of the database. If 'Express Edition', monitor dbSize.

dbSize                    Size of the database in MB. Monitor this value if the edition is 'Express Edition' and this value is close to reaching the 4000 MB maximum. Default=0

mapiVersionNumber         Internal version number of the system. It is a number that is increaed by 100 for each major and minor release. Point releases are the numbers between each 100. Default=0

records                     If successful, records retrieved.

## ExecuteRun

MapiReturn ExecuteRun(string command,

List<KeyValuePair<string, string>> parameters);

### ExecuteRun ActivateDevice

Proxy Activate with a Multiple Activation Key and/or apply the Confirmation ID to remote activate a Device DiskLocator pair.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Activate.

deviceName                Name of the Device to Activate.

deviceMac                 MAC of the Device to Activate.

This required

makUsedToActivate         Multiple Activation Key to Activate the Device with.

### ExecuteRun AddDeviceToDomain

Assign a Device, all Devices in a Collection or View to a Domain.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Add to the Domain.

deviceName                Name of the Device to Add to the Domain.

deviceMac                 MAC of the Device to Add to the Domain.

collectionId              GUID of the Collection to Add all Devices to the Domain.

siteViewId                GUID of the Site View to Add all Devices to the Domain.

farmViewId                GUID of the Farm View to Add all Devices to the Domain.

farmViewName              Name of the Farm View to Add all Devices to the Domain.

or one of these required & resolutions

collectionName            Name of the Collection to Add all Devices to the Domain.

siteViewName              Name of the Site View to Add all Devices to the Domain.

Optional

domain                    Domain to add the Device(s) to. If not included, the first Domain Controller found on the Server is used.

organizationUnit          Organizational Unit to add the Device(s) to. This parameter is optional. If it is not specified, the device is added to the built in Computers container. Child OU's should be delimited with forward slashes, e.g. "ParentOU/ChildOU". Special characters in an OU name, such as '"', '#', '+', ',', ';', '>', '=', must be escaped with a backslash. For example, an OU called "commaIn,TheMiddle" must be specified as "commaIn\\,TheMiddle". The old syntax of delimiting child OU's with a comma is still supported, but deprecated. Note that in this case, the child OU comes first, e.g. "ChildOU,ParentOU".

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun AddDiskVersion

Add one or more new Versions to a Disk. A manifest file for the new Disk Version(s) must exist in the Store.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             GUID of the Disk Locator File to Add the new Disk Version(s) to.

or this required & resolution

diskLocatorName           Name of the Disk Locator File to Add the new Disk Version(s) to.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun ApplyAutoUpdate

Apply Auto Update for a Server or all Servers in a Site.

parameters                  Parameters needed for this Run.

One of these required

serverId                  GUID of the Server to apply Auto Update.

serverName                Name of the Server to apply Auto Update.

siteId                    GUID of the Site to apply Auto Update on all Servers.

siteName                  Name of the Site to apply Auto Update on all Servers.

### ExecuteRun ArchiveAuditTrail

Archive the information in the Audit Trail up to a certain date to a file. When finished, the information archived will be removed from the Audit Trail.

parameters                  Parameters needed for this Run.

This required

fileName                  Name of the file to archive the Audit Trail to. This must be a full file path name.

Optional

endDate                   Last date of information to Archive. If not entered, all information is Archived. Format is yyyy/mm/dd.

purgeData                 1 when the information archived will be removed from the Audit Trail. Default=1

### ExecuteRun AssignAuthGroup

Assign an AuthGroup to have Farm, Site or Collection Authorization. If no Site or Collection is specified, the AuthGroup is given Farm Authorization.

parameters                  Parameters needed for this Run.

One of these required

authGroupId               GUID of the AuthGroup to assign Authorization for.

authGroupName             Name of the AuthGroup to assign Authorization for.

One of these optional

siteId                    GUID of the Site to assign Authorization to for the AuthGroup.

siteName                  Name of the Site to assign Authorization to for the AuthGroup.

collectionId              GUID of the Collection to assign Authorization to for the AuthGroup.

or this optional & resolution

collectionName            Name of the Collection to assign Authorization to for the AuthGroup.

Optional

role                      Authorization Role for the Collection. 300 or 400 can be used. Role can only be used with collectionId or collectionName. 300 is Collection Administrator, and 400 is Collection Operator. Default=400

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun AssignDevice

Assign a Device to a Collection or View. Personal vDisk Devices cannot be moved to another Site.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Assign.

deviceName                Name of the Device to Assign.

deviceMac                 MAC of the Device to Assign.

One of these required

collectionId              GUID of the Collection to Assign a Device or Devices. The Device is moved from whatever Collection it is currently in, to the Collection specified.

siteViewId                GUID of the Site View to Assign a Device.

farmViewId                GUID of the Farm View to Assign a Device.

farmViewName              Name of the Farm View to Assign a Device.

or one of these required & resolutions

collectionName            Name of the Collection to Assign a Device or Devices. The Device is moved from whatever Collection it is currently in, to the Collection specified.

siteViewName              Name of the Site View to Assign a Device.

Optional

copyTemplate              1 if the Template Device for the collection, if it exists, should be used for the property settings of the assigned Device(s). copyTemplate is only valid with collectionId or collectionName.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun AssignDisk

Assign a Disk to an Update Task.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             GUID of the Disk Locator to Assign.

or this required & resolution

diskLocatorName           Name of the Disk Locator File to Assign.

One of these required

updateTaskId              GUID of the Update Task to Assign a Disk.

updateTaskName            Name of the Update Task to Assign a Disk.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun AssignDiskLocator

Assign a Disk Locator to a Device, a Collection or View.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             GUID of the Disk Locator to Assign.

or this required & resolution

diskLocatorName           Name of the Disk Locator File to Assign.

One of these required

deviceId                  GUID of the Device to Assign a Disk Locator.

deviceName                Name of the Device to Assign a Disk Locator.

deviceMac                 MAC of the Device to Assign a Disk Locator.

collectionId              GUID of the Collection to Assign a Disk Locator or Locators to all Devices.

siteViewId                GUID of the Site View to Assign a Disk Locator to all Devices.

farmViewId                GUID of the Farm View to Assign a Disk Locator to all Devices.

farmViewName              Name of the Farm View to Assign a Disk Locator to all Devices.

or one of these required & resolutions

collectionName            Name of the Collection to Assign a Disk Locator or Locators to all Devices.

siteViewName              Name of the Site View to Assign a Disk Locator to all Devices.

Optional

removeExisting            1 to remove the existing Disk Locators before assigning the new one. Default=0

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun AssignServer

Assign a Server to a Site.

parameters                  Parameters needed for this Run.

One of these required

serverId                  GUID of the Server to Assign.

serverName                Name of the Server to Assign.

One of these required

siteId                    GUID of the Site to Assign a Server.

siteName                  Name of the Site to Assign a Server.

### ExecuteRun Boot

Deprecated: use RunWithReturn Boot. Boot a Device, Collection or View.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Boot.

deviceName                Name of the Device to Boot.

deviceMac                 MAC of the Device to Boot.

collectionId              GUID of the Collection to Boot all Devices.

siteViewId                GUID of the Site View to Boot all Devices.

farmViewId                GUID of the Farm View to Boot all Devices.

farmViewName              Name of the Farm View to Boot all Devices.

or one of these required & resolutions

collectionName            Name of the Collection to Boot all Devices.

siteViewName              Name of the Site View to Boot all Devices.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun CancelTask

Cancel a running Task.

parameters                  Parameters needed for this Run.

This required

taskId                    Id of the Task to Cancel.

### ExecuteRun ClearTask

Clear a single or all completed or cancelled Tasks in a Site or the whole Farm.

parameters                  Parameters needed for this Run.

One of these optional

taskId                    Id of the Task to Clear.

siteId                    Site Id of the Tasks to Clear.

siteName                  Site Name of the Tasks to Clear.

### ExecuteRun CopyPasteDevice

Copy properties of one Device to a Device, all the Devices in a Collection, Site View or Farm View.

parameters                  Parameters needed for this Run.

One of these required

deviceIdFrom              GUID of the Device to Copy from.

deviceNameFrom            Name of the Device to Copy from.

deviceMacFrom             Mac of the Device to Copy from.

One of these required

deviceId                  GUID of the Device to Copy to.

deviceName                Name of the Device to Copy to.

deviceMac                 MAC of the Device to Copy to.

collectionId              GUID of the Collection to Copy to.

siteViewId                GUID of the Site View to Copy to.

farmViewId                GUID of the Farm View to Copy to.

farmViewName              Name of the Farm View to Copy to.

or one of these required & resolutions

collectionName            Name of the Collection to Copy to.

siteViewName              Name of the Site View to Copy to.

Optional

properties                If not specified, all are copied. Comma delimited list of properties. Values are: 1 (Description), 2 (Class), 3 (Port), 4 (Disabled), 5 (Boot Behavior), 6 (Disk Assignment), 7 (Personality), 8 (Printer), 9 (Type), 10 (Authentication) and 11 (Logging).

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun CopyPasteDisk

Copy properties of one Disk to a Disk.

parameters                  Parameters needed for this Run.

This required

diskLocatorIdFrom         GUID of the Disk Locator to Copy from.

This required

diskLocatorId             GUID of the Disk Locator to Copy to.

Optional

properties                If not specified, all are copied. Comma delimited list of properties. Values are: 1 (Description), 2 (Class), 3 (Type), 4 (Disk Mode), 5 (Auto Update), 6 (HA), 7 (Active Directory), 8 (Printer), 10 (Version), 11 (Date), 12 (Author), 13 (Title), 14 (Company), 15 (Internal Filename), 16 (Original Filename), 17 (Hardware Target), 18 (Menu Text), 19 (Enabled), 20 (Server), and 21 (Store).

### ExecuteRun CopyPasteServer

Copy properties of one Server to a Server.

parameters                  Parameters needed for this Run.

One of these required

serverIdFrom              GUID of the Server to Copy from.

serverNameFrom            Name of the Server to Copy from.

One of these required

serverId                  GUID of the Server to Copy to.

serverName                Name of the Server to Copy to.

Optional

properties                If not specified, all are copied. Comma delimited list of properties. Values are: 1 (Configuration), 2 (Port), 4 (Active Directory), 5 (Advanced Server), 6 (Advanced Network), 7 (Advanced Pacing), 8 (Advanced Device) and 9 (Logging).

### ExecuteRun CreateDirectory

Create a Directory on the Server specified.

parameters                  Parameters needed for this Run.

One of these required

serverId                  GUID of the Server to create a Directory on.

serverName                Name of the Server to create a Directory on.

This required

path                      Path of the new Directory to create.

### ExecuteRun CreateDiskCancel

Cancel an active CreateDisk.

parameters                  Parameters needed for this Run.

This required

name                      Name of the Disk file that is being created.

One of these required

storeId                   GUID of the Store that the Disk will be a member of.

storeName                 Name of the Store that the Disk will be a member of.

### ExecuteRun DisableCollection

Disable a Collection so Devices that exist in it are Disabled, even if a Device itself is set to be Enabled.

parameters                  Parameters needed for this Run.

This required

collectionId              GUID of the Collection to Disable.

or this required & resolution

collectionName            Name of the Collection to Disable.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun DisableDevice

Disable one or more Devices.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Disable.

deviceName                Name of the Device to Disable.

deviceMac                 MAC of the Device to Disable.

collectionId              GUID of the Collection to Disable all Devices in.

siteViewId                GUID of the Site View to Disable all Devices in.

farmViewId                GUID of the Farm View to Disable all Devices in.

farmViewName              Name of the Farm View to Disable all Devices in.

or one of these required & resolutions

collectionName            Name of the Collection to Disable all Devices in.

siteViewName              Name of the Site View to Disable all Devices in.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun DisableDeviceDiskLocator

Disable a Device's DiskLocator.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Disable the DiskLocator for.

deviceName                Name of the Device to Disable the DiskLocator for.

deviceMac                 MAC of the Device to Disable the DiskLocator for.

This required

diskLocatorId             GUID of the DiskLocator to Disable for the Device.

or this required & resolution

diskLocatorName           Name of the DiskLocator File to Disable for the Device.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun DisableDiskLocator

Disable a DiskLocator so all Devices that have it assigned will not make it available, even if a Device DiskLocator itself is set to be Enabled.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             GUID of the DiskLocator to Disable.

or this required & resolution

diskLocatorName           Name of the DiskLocator File to Disable.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun DiskUpdateCancel

Cancel an active Update Task for an Update Device.

parameters                  Parameters needed for this Run.

This required

updateTaskId              GUID of the Update Task to Cancel.

or this required & resolution

updateTaskName            Name of the Update Task to Cancel.

One of these required

deviceId                  GUID of a specific Update Device to Cancel an Update Task for.

deviceName                Name of a specific Update Device to Cancel an Update Task for.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun DiskUpdateStart

Starts an Update Task.

parameters                  Parameters needed for this Run.

This required

updateTaskId              GUID of the Update Task to Start.

or this required & resolution

updateTaskName            Name of the Update Task to Start.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun DisplayMessage

Deprecated: use RunWithReturn DisplayMessage. Display a message on a Device, a Site, Collection or View.

parameters                  Parameters needed for this Run.

This required

message                   Message to display on the Device(s).

One of these required

deviceId                  GUID of the Device to Display a Message.

deviceName                Name of the Device to Display a Message.

deviceMac                 MAC of the Device to Display a Message.

collectionId              GUID of the Collection to Display a Message on all Devices.

siteViewId                GUID of the Site View to Display a Message all Devices.

farmViewId                GUID of the Farm View to Display a Message on all Devices.

farmViewName              Name of the Farm View to Display a Message on all Devices.

or one of these required & resolutions

collectionName            Name of the Collection to Display a Message on all Devices.

siteViewName              Name of the Site View to Display a Message on all Devices.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun EnableCollection

Enable a Collection so Devices that exist in it are Enabled, if the Device itself is not set to be Disabled.

parameters                  Parameters needed for this Run.

This required

collectionId              GUID of the Collection to Enable.

or this required & resolution

collectionName            Name of the Collection to Enable.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun EnableDevice

Enable one or more Devices. If the Device's Collection is Disabled, that overrides the Device setting.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Enable.

deviceName                Name of the Device to Enable.

deviceMac                 MAC of the Device to Enable.

collectionId              GUID of the Collection to Enable all Devices in.

siteViewId                GUID of the Site View to Enable all Devices in.

farmViewId                GUID of the Farm View to Enable all Devices in.

farmViewName              Name of the Farm View to Enable all Devices in.

or one of these required & resolutions

collectionName            Name of the Collection to Enable all Devices in.

siteViewName              Name of the Site View to Enable all Devices in.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun EnableDeviceDiskLocator

Enable a Device's DiskLocator. If the DiskLocator is Disabled, that overrides the Device DiskLocator setting.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Enable the DiskLocator for.

deviceName                Name of the Device to Enable the DiskLocator for.

deviceMac                 MAC of the Device to Enable the DiskLocator for.

This required

diskLocatorId             GUID of the DiskLocator to Enable for the Device.

or this required & resolution

diskLocatorName           Name of the DiskLocator to Enable for the Device.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun EnableDiskLocator

Enable a DiskLocator so Devices that have it assigned will make it available, if the Device DiskLocator itself is not set to be Disabled.

parameters &nnbsp;                Parameters needed for this Run.

This required

diskLocatorId             GUID of the DiskLocator to Enable.

or this required & resolution

diskLocatorName           Name of the DiskLocator File to Enable.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun ExportDisk

Export the disk stack to a manifest file.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             GUID of the Disk Locator that identifies the disk to export.

or this required & resolution

diskLocatorName           Name of the Disk Locator that identifies the disk to export.

Optional

version                   Version to use as the start of the export. The export will include all versions starting with this to the highest one.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun ExportOemLicenses

Oem Only: Export the Oem Licenses for the Devices to the fileName specified.

parameters                  Parameters needed for this Run.

This required

fileName                  Name of the file to export the Oem Licenses to. This must be a full file path name.

One of these required

deviceId                  GUID of the Device, or comma-delimited list of Device GUIDs to Export Oem Licenses to the fileName specified.

deviceName                Name of the Device, or comma-delimited list of Device Names to Export Oem Licenses to the fileName specified.

deviceMac                 MAC of the Device, or comma-delimited list of Device MACs to Export Oem Licenses to the fileName specified.

collectionId              GUID of the Collection to Export all Device Oem Licenses to the fileName specified.

siteViewId                GUID of the Site View to Export all Device Oem Licenses to the fileName specified.

farmViewId                GUID of the Farm View to Export all Device Oem Licenses to the fileName specified.

farmViewName              Name of the Farm View to Export all Device Oem Licenses to the fileName specified.

or one of these required & resolutions

collectionName            Name of the Collection to Export all Device Oem Licenses to the fileName specified.

siteViewName              Name of the Site View to Export all Device Oem Licenses to the fileName specified.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun ForceInventory

Force the Inventory service to refresh its Inventory Table.

### ExecuteRun ImportDatabase

Import Devices from the version 4.x mdb database fileName specified.

parameters                  Parameters needed for this Run.

This required

fileName                  Name of the database mdb file to import the Devices from. This must be a full file path name.

This required

collectionId              GUID of the Collection to import the Devices into.

or this required & resolution

collectionName            Name of the Collection to import the Devices into.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun ImportDevices

Import Devices from the contents of the comma or tab delimited fileName specified. Each record needs to have Device Name, Mac Address, Site Name, Collection Name, optional Description and optional Type. Description must exist for Type to be included, but it can have 0 length. Type can be 1 when it performs test of Disks, 2 when it performs maintenance on Disks, and 0 otherwise.

parameters                  Parameters needed for this Run.

This required

fileName                  Name of the file to import the Devices from. This must be a full file path name.

One of these optional

collectionId              GUID of the Collection to import the Devices into.

siteId                    GUID of the Site to import the Devices into.

siteName                  Name of the Site to import the Devices into.

or this optional & resolution

collectionName            Name of the Collection to import the Devices into.

Optional

copyTemplate              1 if the Template Device for the collection, if it exists, should be used for the property settings of the imported Devices.

doNotCreateNewSites       1 if new Sites found in the file should not be created. Default=0

doNotCreateNewCollections  1 if new Collections found in the file should not be created. Default=0

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun ImportOemLicenses

Oem Only: Import the Oem Licenses from the contents of the fileName specified.

parameters                  Parameters needed for this Run.

This required

fileName                  Name of the file to import the Oem Licenses from. This must be a full file path name.

### ExecuteRun MarkDown

Mark Down a Device, Collection, View, Server or Site.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Mark Down.

deviceName                Name of the Device to Mark Down.

deviceMac                 MAC of the Device to Mark Down.

collectionId              GUID of the Collection to Mark Down all Devices.

siteViewId                GUID of the Site View to Mark Down all Devices.

siteId                    GUID of the Site. Can be used alone to Mark Down all Servers and Devices in the Site.

siteName                  Name of the Site. Can be used alone to Mark Down all Servers and Devices in the Site.

farmViewId                GUID of the Farm View to Mark Down all Devices.

farmViewName              Name of the Farm View to Mark Down all Devices.

diskLocatorId             GUID of the DiskLocator to Mark Down all Devices.

serverId                  GUID of the Server to Mark Down.

serverName                Name of the Server to Mark Down.

or one of these required & resolutions

collectionName            Name of the Collection to Mark Down all Devices.

siteViewName              Name of the Site View to Mark Down all Devices.

diskLocatorName           Name of the DiskLocator to Mark Down all Devices.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun MergeDisk

Merge the Disk.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             GUID of the Disk Locator File to Merge.

or this required & resolution

diskLocatorName           Name of the Disk Locator File to Merge.

Optional

access                    Access to set the version to when merge is finished. Default value is found in the Farm mergeMode setting. Values are: 0 (Production), 1 (Test) and 2 (Maintenance), Min=0, Max=2

base                      When 1, specifies to create a new base from last base plus all updates from that base. The default is to merge all updates from the last base by default.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun PromoteDiskVersion

Commit the changes made in the current Maintenance or a Test version. Promotes the Maintenance version or a Test version to a Test or new Production version.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             GUID of the Disk Locator File to Promote the Disk Version of.

or this required & resolution

diskLocatorName           Name of the Disk Locator File to Promote the Disk Version of.

Optional

scheduledDate             Date/Time the new disk version will become available. Format is: YYYY-MM-DD HH:MM

testVersion               Specifies the Test version number that should be Promoted to Production.

test                      Set the mode of the Maintenance version to Test when 1. Default is 0.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun Reboot

Deprecated: use RunWithReturn Reboot. Reboot a Device, Collection or View.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Reboot.

deviceName                Name of the Device to Reboot.

deviceMac                 MAC of the Device to Reboot.

collectionId              GUID of the Collection to Reboot all Devices.

siteViewId                GUID of the Site View to Reboot all Devices.

farmViewId                GUID of the Farm View to Reboot all Devices.

farmViewName              Name of the Farm View to Reboot all Devices.

diskLocatorId             GUID of the DiskLocator to Reboot all Devices.

or one of these required & resolutions

collectionName            Name of the Collection to Reboot all Devices.

siteViewName              Name of the Site View to Reboot all Devices.

diskLocatorName           Name of the DiskLocator to Reboot all Devices.

Optional

message                   Message to display before rebooting the Device(s). Default=The target device is being shutdown remotely by the Console.

delay                     Number of seconds to delay before rebooting the Device(s). Default=10

version                   Version of the Disk to Reboot all Devices for. This is used with diskLocatorId or diskLocatorName.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun RemoveAuthGroup

Remove Farm, Site or Collection Authorization for an AuthGroup. If no Site or Collection is specified, Farm Authorization is removed for the AuthGroup.

parameters                  Parameters needed for this Run.

One of these required

authGroupId               GUID of the AuthGroup to remove Authorization for.

authGroupName             Name of the AuthGroup to remove Authorization for.

One of these optional

siteId                    GUID of the Site to remove Authorization for the AuthGroup.

siteName                  Name of the Site to remove Authorization for the AuthGroup.

collectionId              GUID of the Collection to remove Authorization for the AuthGroup.

or this optional & resolution

collectionName            Name of the Collection to remove Authorization for the AuthGroup.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun RemoveDevice

Remove a Device from a View.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Remove.

deviceName                Name of the Device to Remove.

deviceMac                 MAC of the Device to Remove.

One of these required

siteViewId                GUID of the Site View to Remove the Devices from.

farmViewId                GUID of the Farm View to Remove the Devices from.

farmViewName              Name of the Farm View to Remove the Devices from.

or this required & resolution

siteViewName              Name of the Site View to Remove the Devices from.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun RemoveDeviceFromDomain

Remove a Device, all Devices in a Collection or View from a Domain.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Remove from the Domain.

deviceName                Name of the Device to Remove from the Domain.

deviceMac                 MAC of the Device to Remove from the Domain.

collectionId              GUID of the Collection to Remove all Devices from the Domain.

siteViewId                GUID of the Site View to Remove all Devices from the Domain.

farmViewId                GUID of the Farm View to Remove all Devices from the Domain.

farmViewName              Name of the Farm View toRemove all Devices from the Domain.

or one of these required & resolutions

collectionName            Name of the Collection to Remove all Devices from the Domain.

siteViewName              Name of the Site View to Remove all Devices from the Domain.

Optional

domain                    Domain to remove the Device(s) from. If not included, the first Domain Controller found on the Server is used.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun RemoveDirectory

Remove a Directory on the Server specified.

parameters                  Parameters needed for this Run.

One of these required

serverId                  GUID of the Server to remove a Directory from. The directory must be empty to be removed.

serverName                Name of the Server to remove a Directory from. The directory must be empty to be removed.

This required

path                      Path of the Directory to remove.

### ExecuteRun RemoveDisk

Remove a Disk from an Update Task.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             GUID of the Disk Locator to Remove.

or this required & resolution

diskLocatorName           Name of the Disk Locator File to Remove.

One of these optional

updateTaskId              GUID of the Update Task to Remove a Disk.

updateTaskName            Name of the Update Task to Remove a Disk.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun RemoveDiskLocator

Remove a Disk Locator from a Device, Collection, View, or Site.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             GUID of the Disk Locator to Remove.

or this required & resolution

diskLocatorName           Name of the Disk Locator File to Remove.

One of these optional

deviceId                  GUID of the Device to Remove a Disk Locator.

deviceName                Name of the Device to Remove a Disk Locator.

deviceMac                 MAC of the Device to Remove a Disk Locator.

collectionId              GUID of the Collection to Remove a Disk Locator or Locators from all Devices.

siteViewId                GUID of the Site View to Remove a Disk Locator from all Devices.

farmViewId                GUID of the Farm View to Remove a Disk Locator from all Devices.

farmViewName              Name of the Farm View to Remove a Disk Locator from all Devices.

or one of these optional & resolutions

collectionName            Name of the Collection to Remove a Disk Locator or Locators from all Devices.

siteViewName              Name of the Site View to Remove a Disk Locator from all Devices.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun ResetDatabaseConnection

Cause the database location to be reloaded.

### ExecuteRun ResetDeviceForDomain

Reset a Device, all Devices in a Collection or View for a Domain.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Reset for the Domain.

deviceName                Name of the Device to Reset for the Domain.

deviceMac                 MAC of the Device to Reset for the Domain.

collectionId              GUID of the Collection to Reset all Devices for the Domain.

siteViewId                GUID of the Site View to Reset all Devices for the Domain.

farmViewId                GUID of the Farm View to Reset all Devices for the Domain.

farmViewName              Name of the Farm View to Reset all Devices for the Domain.

or one of these required & resolutions

collectionName            Name of the Collection to Reset all Devices for the Domain.

siteViewName              Name of the Site View to Reset all Devices for the Domain.

Optional

domain                    Domain to Reset the Device(s) for. If not included, the first Domain Controller found on the Server is used.

organizationUnit          Organizational Unit to reset the Device(s) to. This parameter is optional. If it is not specified, the account remains in its existing OU. Child OU's should be delimited with forward slashes, e.g. "ParentOU/ChildOU". Special characters in an OU name, such as '"', '#', '+', ',', ';', '>', '=', must be escaped with a backslash. For example, an OU called "commaIn,TheMiddle" must be specified as "commaIn\\,TheMiddle". The old syntax of delimiting child OU's with a comma is still supported, but deprecated. Note that in this case, the child OU comes first, e.g. "ChildOU,ParentOU".

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

### ExecuteRun RestartStreamService

Restart the Stream Service on a Server or all Servers in a Site.

parameters                  Parameters needed for this Run.

One of these required

serverId                  GUID of the Server to restart the Stream Service.

serverName                Name of the Server to restart the Stream Service.

siteId                    GUID of the Site to restart the Stream Service on all Servers.

siteName                  Name of the Site to restart the Stream Service on all Servers.

### ExecuteRun RevertDiskVersion

Set the existing highest version disk to Maintenance or Test mode. A specified version can be reverted to Test mode if there are no Production versions higher than it. If the mode is Test, it can be set to Maintenance.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             GUID of the Disk Locator File to Revert.

or this required & resolution

diskLocatorName           Name of the Disk Locator File to Revert.

Optional

version                   Specifies the version number that should be Reverted to Test mode.

test                      If reverting the highest version and 1 then set the access to Test, otherwise set it to Maintenance.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun SetOverrideVersion

Specify a Disk Version all Production Devices will boot from.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             GUID of the Disk Locator File to Override the Production Version for.

or this required & resolution

diskLocatorName           Name of the Disk Locator File to Override the Production Version for.

Optional

version                   Version to set as the Override Production Version. If Version is not included and if there is an Override Production Version, then no longer have it as the Override Version.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun Shutdown

Deprecated: use RunWithReturn Shutdown. Shutdown a Device, Collection or View.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Shutdown.

deviceName                Name of the Device to Shutdown.

deviceMac                 MAC of the Device to Shutdown.

collectionId              GUID of the Collection to Shutdown all Devices.

siteViewId                GUID of the Site View to Shutdown all Devices.

farmViewId                GUID of the Farm View to Shutdown all Devices.

farmViewName              Name of the Farm View to Shutdown all Devices.

diskLocatorId             GUID of the DiskLocator to Shutdown all Devices.

or one of these required & resolutions

collectionName            Name of the Collection to Shutdown all Devices.

siteViewName              Name of the Site View to Shutdown all Devices.

diskLocatorName           Name of the DiskLocator to Shutdown all Devices.

Optional

message                   Message to display before shutting down the Device(s). Default=The target device is being shutdown remotely by the Console.

delay                     Number of seconds to delay before shutting down the Device(s). Default=10

version                   Version of the Disk to Shutdown all Devices for. This is used with diskLocatorId or diskLocatorName.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun StartDeviceDiskTempVersionMode

Set a Temporary Disk Version for the specified Device and optional DiskLocator. The Temporary Disk Version uses the production version that all production Devices boot from. Once set, the Device boots this Temporary Disk Version instead of any currently assigned vDisk. Not supported for non-production and Personal vDisk Devices. Cannot be done when the the Device already has a Temporary Disk Version, when the DiskLocator is using server side persistent cache mode or the active production version is in private mode.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to start to use a temporary disk version.

deviceName                Name of the Device to start to use a temporary disk version.

deviceMac                 MAC of the Device to start to use a temporary disk version.

This optional

diskLocatorId             GUID of the Disk Locator to use a temporary version of. If not specified, the only Disk Locator assigned to the Device is used.

or this optional & resolution

diskLocatorName           Name of the Disk Locator to use a temporary version of. If not specified, the only Disk Locator assigned to the Device is used.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun StartStreamService

Start the Stream Service on a Server or all Servers in a Site.

parameters                  Parameters needed for this Run.

One of these required

serverId                  GUID of the Server to start the Stream Service.

serverName                Name of the Server to start the Stream Service.

siteId                    GUID of the Site to start the Stream Service on all Servers.

siteName                  Name of the Site to start the Stream Service on all Servers.

### ExecuteRun StopDeviceDiskTempVersionMode

Unset the Temporary Disk Version for the specified Device. The Device must not currently be booted. Once removed, the Device again uses any currently assigned vDisk when booted.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to no longer use a temporary disk version for.

deviceName                Name of the Device to no longer use a temporary disk version for.

deviceMac                 MAC of the Device to no longer use a temporary disk version for.

diskLocatorId             GUID of the DiskLocator to no longer use temporary disk versions for.

siteId                    GUID of the Site for resolution of the diskLocatorName.

siteName                  Name of the Site for resolution of the diskLocatorName.

or this required & resolution

diskLocatorName           Name of the DiskLocator to no longer use temporary disk versions for.

This optional & resolution

version                   Version of the DiskLocator to no longer use temporary disk versions for.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

diskLocatorId             GUID of the DiskLocator to no longer use temporary disk versions for.

diskLocatorName           Name of the DiskLocator to no longer use temporary disk versions for.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun StopStreamService

Stop the Stream Service on a Server or all Servers in a Site.

parameters                  Parameters needed for this Run.

One of these required

serverId                  GUID of the Server to stop the Stream Service.

serverName                Name of the Server to stop the Stream Service.

siteId                    GUID of the Site to stop the Stream Service on all Servers.

siteName                  Name of the Site to stop the Stream Service on all Servers.

### ExecuteRun UnlockAllDisk

Remove all locks for a Disk.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             GUID of the Disk Locator to remove all locks for the Disk.

or this required & resolution

diskLocatorName           Name of Disk Locator to remove all locks for the Disk.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun UnlockDisk

Remove lock for the Disk.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             GUID of the Disk Locator to remove a lock for the Disk.

or this required & resolution

diskLocatorName           Name of the Disk Locator to remove a lock for the Disk.

Optional

ownerId                   GUID of the Owner of the Disk Lock.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

### ExecuteRun ValidateDirectory

Validate a Directory on the Server specified.

parameters                  Parameters needed for this Run.

One of these required

serverId                  GUID of the Server to validate a Directory on.

serverName                Name of the Server to validate a Directory on.

This required

path                      Path of the Directory to validate.

This optional

readOnly                  1 when the directory should be validated for a managed read-only store.

## ExecuteRunWithReturn

MapiReturn ExecuteRunWithReturn(string command,

List<KeyValuePair<string, string>> parameters,

out string rv);

### ExecuteRunWithReturn Boot

Boot a Device, Collection or View. Returns a taskId of the Task being run. With the taskId, call ReturnWithReturn TaskStatus to get the percent complete, Get Task to get the results, and Run CancelTask to stop it early. The Task result has the deviceName/value of the devices that succeeded in the first name/value pair of each record of the XML.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Boot.

deviceName                Name of the Device to Boot.

deviceMac                 MAC of the Device to Boot.

collectionId              GUID of the Collection to Boot all Devices.

siteViewId                GUID of the Site View to Boot all Devices.

farmViewId                GUID of the Farm View to Boot all Devices.

farmViewName              Name of the Farm View to Boot all Devices.

deviceIdList              Comma delimited list of GUIDs of the Devices to Boot. Maximum length is 8000 characters.

deviceNameList            Comma delimited list of Names of the Devices to Boot. Maximum length is 8000 characters.

deviceMacList             Comma delimited list of MACs of the Devices to Boot. Maximum length is 8000 characters.

or one of these required & resolutions

collectionName            Name of the Collection to Boot all Devices.

siteViewName              Name of the Site View to Boot all Devices.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn CommandActions

Get a comma delimited list of Command Actions.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn CreateDisk

Create a Disk and the Disk Locator for it. Return the GUID of the DiskLocator created. If "" is returned as the GUID, then call CreateDiskStatus to get the final GUID when processing finishes.

parameters                  Parameters needed for this Run.

This required

name                      Name of the Disk file to be created.

This required

size                      Size of the disk in Megabytes for a fixed size disk. Maximum size in Megabytes for a dynamically sized disk. Min=1, VHD Max=2088960, VHDX Max=67108864

One of these required

storeId                   GUID of the Store that the Disk will be a member of.

storeName                 Name of the Store that the Disk will be a member of.

One of these required

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these optional

serverId                  GUID of the only Server for this Disk.

serverName                Name of the only Server for this Disk.

Optional

description               Description of the Disk that will be placed in the Disk Locator.

enabled                   The Disk will be created disabled if set to 0. It is created Enabled by default. Default=1

format                    Format of the image. Values are: 0 (VHD), 1 (VHDX), Default=0

type                      Type that will be created. 1 for dynamic, or 0 for fixed. Default=1 for VHDX, 0 for VHD

vhdBlockSize              Block size in KB. For VHD it is only used with Dynamic type. Tested sizes for VHD are 512, 2048, and 16384. VHD Min=512, Max=16384, Default=2048. For VHDX it is used for all types. Tested size for VHDX is 32768. VHDX Min=1024, Max= 262144, Default=32768.

logicalSectorSize         Only used with VHDX format. Logical Sector Size. Values are: 512, 4096, Default=512

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn CreateDiskStatus

Get the Percent Finished for an active CreateDisk. When finished, the GUID of the DiskLocator created is returned.

parameters                  Parameters needed for this Run.

This required

name                      Name of the Disk file that is being created.

One of these required

storeId                   GUID of the Store that the Disk will be a member of.

storeName                 Name of the Store that the Disk will be a member of.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn CreateMaintenanceVersion

Create a Maintenance version for the Disk Locator. Return the name of the new version file.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             GUID of the Disk Locator File to Enable Disk Maintenance on.

or this required & resolution

diskLocatorName           Name of the Disk Locator File to Enable Disk Maintenance on.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn DeviceCount

Get count of Devices in a Collection or View.

parameters                  Parameters needed for this Run.

One of these required

collectionId              GUID of the Collection to get the Device Count of.

siteViewId                GUID of the Site View to get the Device Count of.

farmViewId                GUID of the Farm View to get the Device Count of.

farmViewName              Name of the Farm View to get the Device Count of.

or one of these required & resolutions

collectionName            Name of the Collection to get the Device Count of.

siteViewName              Name of the Site View to get the Device Count of.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn DiskLocatorCount

Get count of Disk Locators for a Site and Type.

parameters                  Parameters needed for this Run.

One of these required

siteId                    GUID of the Site to get the Disk Locator Count of.

siteName                  Name of the Site to get the Disk Locator Count of.

One of these optional

single                    Include single server connection when set to 1. If this and All are not included, both connection types are included.

all                       Include all server connections for the store when set to 1. If this and Single are not included, both connection types are included.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn DisplayMessage

Display a message on a Device, a Site, Collection or View. Returns a taskId of the Task being run. With the taskId, call ReturnWithReturn TaskStatus to get the percent complete, Get Task to get the results, and Run CancelTask to stop it early. The Task result has the deviceName/value of the devices that succeeded in the first name/value pair of each record of the XML.

parameters                  Parameters needed for this Run.

This required

message                   Message to display on the Device(s).

One of these required

deviceId                  GUID of the Device to Display a Message.

deviceName                Name of the Device to Display a Message.

deviceMac                 MAC of the Device to Display a Message.

collectionId              GUID of the Collection to Display a Message on all Devices.

siteViewId                GUID of the Site View to Display a Message all Devices.

farmViewId                GUID of the Farm View to Display a Message on all Devices.

farmViewName              Name of the Farm View to Display a Message on all Devices.

deviceIdList              Comma delimited list of GUIDs of the Devices to Display a Message. Maximum length is 8000 characters.

deviceNameList            Comma delimited list of Names of the Devices to Display a Message. Maximum length is 8000 characters.

deviceMacList             Comma delimited list of MACs of the Devices to Display a Message. Maximum length is 8000 characters.

or one of these required & resolutions

collectionName            Name of the Collection to Display a Message on all Devices.

siteViewName              Name of the Site View to Display a Message on all Devices.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn Enabled

Return 1 if a Collection, Device, DiskLocator, or Device/DiskLocator is enabled. If a collectionName or diskLocatorName is specified, siteName or siteId must be included. If both the Device and DiskLocator are specified, the Enabled setting for the combination is returned.

parameters                  Parameters needed for this Run.

This optional

collectionId              Collection GUID, to see if it is enabled.

or this optional & resolution

collectionName            Collection name, to see if it is enabled.

One of these optional

deviceId                  Device GUID, to see if it is enabled. If diskLocatorName or diskLocatorId are also included the enabled setting for the combination is returned.

deviceName                Device name, to see if it is enabled. If diskLocatorName or diskLocatorId are also included the enabled setting for the combination is returned.

deviceMac                 MAC of the Device, to see if it is enabled. If diskLocatorName or diskLocatorId are also included the enabled setting for the combination is returned.

This optional

diskLocatorId             DiskLocator GUID, to see if it is enabled. If deviceName or deviceId are also included the enabled setting for the combination is returned.

or this optional & resolution

diskLocatorName           DiskLocator name, to see if it is enabled. If deviceName or deviceId are also included the enabled setting for the combination is returned.

One of these resolutions when needed

siteName                  Name of the Site.

siteId                    GUID of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn Exists

Return 1 if a Site, Server, Collection, View, Device, Store, Update Task or Virtual Hosting Pool Name is already used. If a collectionName, siteViewName, updateTaskName or virtualHostingPoolName is specified, siteName or siteId must be included.

parameters                  Parameters needed for this Run.

One of these required

siteName                  Name of the Site.

serverName                Server name, to see if it is already used in the Farm.

farmViewName              Farm View name, to see if it is already used in the Farm.

deviceName                Device name, to see if it is already used in the Farm.

deviceMac                 Device MAC, to see if it is already used in the Farm.

storeName                 Store name, to see if it is already used.

or one of these required & resolutions

collectionName            Collection name, to see if it is already used in a Site.

siteViewName              Site View name, to see if it is already used in the Site.

virtualHostingPoolName    Virtual Hosting Pool name, to see if it is already used in a Site.

updateTaskName            Update Task name, to see if it is already used in a Site.

diskLocatorName           DiskLocator name, to see if it is already used in a Site.

One of these resolutions when needed

siteName                  Name of the Site.

siteId                    GUID of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn ImportDisk

Import a Disk. It will add a Disk Locator for the Disk to the Site. A manifest file must exist in the Store. The return value is the GUID of the DiskLocator added.

parameters                  Parameters needed for this Run.

This required & resolution

diskLocatorName           Name of the Disk Locator File. It is unique within the Store. ASCII Max Length=52

One of these optional

serverId                  GUID of the single Server that this Disk Locator is assigned to. It is not used with serverName. Default=null Length=36

serverName                Name of the single Server that this Disk Locator is assigned to. It is not used with serverId. Default=null

Optional

description               User description. Default="" Max Length=250

menuText                  Text that is displayed in the Boot Menu. If this field has no value, the name value is used. Default="" ASCII Max Length=64

enabled                   1 when this disk can be booted, 0 otherwise. Default=1

rebalanceEnabled          1 when this Server can automatically rebalance Devices, 0 otherwise. Default=0

rebalanceTriggerPercent   Percent over fair load that triggers a dynamic Device rebalance. Min=5, Max=5000, Default=25

subnetAffinity            Qualifier for subnet affinity when assigning a Server. 0=None, 1=Best Effort, 2=Fixed. Min=0, Max=2, Default=0

format                    Format of the image. Values are: 0 (VHD), 1 (VHDX), Default=0

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn ListDirectories

Look for Directories or Drives on the Server specified. Return a comma delimited list of the Directories or Drives found.

parameters                  Parameters needed for this Run.

One of these required

serverId                  GUID of the Server to get a list of Directories or Drives.

serverName                Name of the Server to get a list of Directories or Drives.

Optional

path                      Path to get list of Directories for. If not specified, the Drives are returned.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn MaintenanceVersionExists

Return 1 if the if the DiskLocator has a maintenance version, 0 otherwise.

parameters                  Parameters needed for this Run.

This required

diskLocatorId             DiskLocator GUID, to see if it has a maintenance version.

or this required & resolution

diskLocatorName           DiskLocator name, to see if it has a maintenance version.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn MappedDiskId

If there is currently a mapped disk, return the diskLocatorId of the mapped disk.

parameters                  Parameters needed for this Run.

One of these optional

serverId                  GUID of the Server.

serverName                Name of the Server.

One of these optional

storeId                   GUID of the Store.

storeName                 Name of the Store.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn MappedDriveLetter

If there is currently a Mapped Drive, return the Letter of the Drive.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn MinimumLastAutoAddDeviceNumber

Get the minimum that the Device Number of the last Auto Added Device can be.

parameters                  Parameters needed for this Run.

This required

collectionId              GUID of the Collection to get the Minimum lastAutoAddDeviceNumber for.

or this required & resolution

collectionName            Name of the Collection to get the Minimum lastAutoAddDeviceNumber for.

Optional

autoAddPrefix             The string put before the Device Number for Auto Add.

autoAddSuffix             The string put after the Device Number for Auto Add.

autoAddNumberLength       The maximum length of the Device Number for Auto Add. This length plus the autoAddPrefix length plus the autoAddSuffix length must be less than 16.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn RebalanceDevices

Rebalance Devices for a Server. When successful, returns the number of Devices affected.

parameters                  Parameters needed for this Run.

One of these required

serverId                  GUID of the Server to Rebalance Devices on, serverName.

serverName                Name of the Server to Rebalance Devices on, serverId.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn Reboot

Reboot a Device, Collection or View. Returns a taskId of the Task being run. With the taskId, call ReturnWithReturn TaskStatus to get the percent complete, Get Task to get the results, and Run CancelTask to stop it early. The Task result has the deviceName/value of the devices that succeeded in the first name/value pair of each record of the XML.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Reboot.

deviceName                Name of the Device to Reboot.

deviceMac                 MAC of the Device to Reboot.

collectionId              GUID of the Collection to Reboot all Devices.

siteViewId                GUID of the Site View to Reboot all Devices.

farmViewId                GUID of the Farm View to Reboot all Devices.

farmViewName              Name of the Farm View to Reboot all Devices.

diskLocatorId             GUID of the DiskLocator to Reboot all Devices.

deviceIdList              Comma delimited list of GUIDs of the Devices to Reboot. Maximum length is 8000 characters.

deviceNameList            Comma delimited list of Names of the Devices to Reboot. Maximum length is 8000 characters.

deviceMacList             Comma delimited list of MACs of the Devices to Reboot. Maximum length is 8000 characters.

or one of these required & resolutions

collectionName            Name of the Collection to Reboot all Devices.

siteViewName              Name of the Site View to Reboot all Devices.

diskLocatorName           Name of the DiskLocator to Reboot all Devices.

Optional

message                   Message to display before rebooting the Device(s). Default=The target device is being shutdown remotely by the Console.

delay                     Number of seconds to delay before rebooting the Device(s). Default=10

version                   Version of the Disk to Reboot all Devices for. This is used with diskLocatorId or diskLocatorName.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn ReportBug

Report a bug at individual server level or at site level. Return the id of the long running task.

parameters                  Parameters needed for this Run.

One of these required

siteId                    GUID of the Site.

serverId                  GUID of the Server.

or one of these required & resolutions

siteName                  Name of the Site.

serverName                Name of the Server.

This required

Summary                   Short summary describing the problem.

This optional

srNumber                  Service Request number of the reported problem.

This optional

Description               Description of the reported problem.

This optional

Path                      Path where problem report bundle is saved.

This optional

DateTime                  DateTime around which the reported problem occured.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn ServerCount

Get count of Servers in a Site.

parameters                  Parameters needed for this Run.

One of these required

siteId                    GUID of the Site to get the Server Count of.

siteName                  Name of the Site to get the Server Count of.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn ServerName

Return the name of the Server the SoapServer is running on.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn ServerStoreActiveDeviceCount

Get the count of Devices currently connected to any vdisk served from the Store by the Server.

parameters                  Parameters needed for this Run.

One of these required

serverId                  GUID of the Server.

serverName                Name of the Server.

One of these required

storeId                   GUID of the Store.

storeName                 Name of the Store.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn Shutdown

Shutdown a Device, Collection or View. Returns a taskId of the Task being run. With the taskId, call ReturnWithReturn TaskStatus to get the percent complete, Get Task to get the results, and Run CancelTask to stop it early. The Task result has the deviceName/value of the devices that succeeded in the first name/value pair of each record of the XML.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Shutdown.

deviceName                Name of the Device to Shutdown.

deviceMac                 MAC of the Device to Shutdown.

collectionId              GUID of the Collection to Shutdown all Devices.

siteViewId                GUID of the Site View to Shutdown all Devices.

farmViewId                GUID of the Farm View to Shutdown all Devices.

farmViewName              Name of the Farm View to Shutdown all Devices.

diskLocatorId             GUID of the DiskLocator to Shutdown all Devices.

deviceIdList              Comma delimited list of GUIDs of the Devices to Shutdown. Maximum length is 8000 characters.

deviceNameList            Comma delimited list of Names of the Devices to Shutdown. Maximum length is 8000 characters.

deviceMacList             Comma delimited list of MACs of the Devices to Shutdown. Maximum length is 8000 characters.

or one of these required & resolutions

collectionName            Name of the Collection to Shutdown all Devices.

siteViewName              Name of the Site View to Shutdown all Devices.

diskLocatorName           Name of the DiskLocator to Shutdown all Devices.

Optional

message                   Message to display before shutting down the Device(s). Default=The target device is being shutdown remotely by the Console.

delay                     Number of seconds to delay before shutting down the Device(s). Default=10

version                   Version of the Disk to Shutdown all Devices for. This is used with diskLocatorId or diskLocatorName.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn StoreFreeSpace

Get the free megabytes available in the Store.

parameters                  Parameters needed for this Run.

One of these required & resolutions

storeId                   GUID of the Store.

storeName                 Name of the Store.

One of these resolutions when needed

serverId                  GUID of the Server to use to determine the free space in the Store.

serverName                Name of the Server to use to determine the free space in the Store.

siteId                    GUID of the Site.

siteName                  Name of the Site.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn TaskStatus

Get the status of a Task in percent complete.

parameters                  Parameters needed for this Run.

This required

taskId                    Id of the Task to get the Status of.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn UpdateBDM

Update the BDM Partition for a Device, Collection or View. Returns a taskId of the Task being run. With the taskId, call ReturnWithReturn TaskStatus to get the percent complete, Get Task to get the results, and Run CancelTask to stop it early. The Task result has the deviceName/value of the devices that succeeded in the first name/value pair of each record of the XML.

parameters                  Parameters needed for this Run.

One of these required

deviceId                  GUID of the Device to Update.

deviceName                Name of the Device to Update.

collectionId              GUID of the Collection to Update all BDM Devices.

siteViewId                GUID of the Site View to Update all BDM Devices.

farmViewId                GUID of the Farm View to Update all BDM Devices.

farmViewName              Name of the Farm View to Update all BDM Devices.

deviceIdList              Comma delimited list of GUIDs of the Devices to Update. Maximum length is 8000 characters.

deviceNameList            Comma delimited list of names of the Devices to Update. Maximum length is 8000 characters.

or one of these required & resolutions

collectionName            Name of the Collection to Update all BDM Devices.

siteViewName              Name of the Site View to Update all BDMDevices.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

rv                          If successful, this rv is filled with a string.

### ExecuteRunWithReturn UploadCeip

Perform a one time upload of CEIP data. Return upload Id if successful.

parameters                  Parameters needed for this Run.

This optional

oneTimeUpload             1 to perform a one time upload.

rv                          If successful, this rv is filled with a string.

## ExecuteSet

MapiReturn ExecuteSet(string command,

List<KeyValuePair<string, string>> parameters,

List<KeyValuePair<string, string>> fields);

### ExecuteSet AuthGroup

Set one or more field values for an AuthGroup.

parameters                  Parameters needed to identify the record to be changed.

One of these required

authGroupId               GUID of the AuthGroup to Set.

authGroupName             Name of the AuthGroup to Set.

record                      Record containing the new values for fields to be changed.

authGroupName             Name of the Active Directory or Windows Group. Max Length=450

description               User description. Default="" Max Length=250

### ExecuteSet CeipData

Set one or more field values for CEIP data.

parameters                  Parameters needed to identify the record to be changed.

Optional

uuid                      CEIP UUID of this Farm. This is optional since there is only one.

record                      Record containing the new values for fields to be changed.

enabled                &nbsnbsp;  1 if CEIP is enabled, otherwise 0. Min=0, Max=1

nextUpload                Date and time next CEIP upload is due if enabled is 1. Default=null

inProgress                1 if an upload is currently in progress, otherwise 0. Default=0

serverId                  ID of server that is currently uploading, null if inProgress is 0. Default=null Length=36

oneTimeUpload             1 to perform a one time upload. Default=0

### ExecuteSet CisData

Set one or more field values for CIS data.

parameters                  Parameters needed to identify the record to be changed.

Optional

cisDataId                 CIS UUID of this Farm. This is optional since there is only a single record.

record                      Record containing the new values for fields to be changed.

userName                  Username used to obtain the token Default=null Max Length=255

path                      Path where the last problem report bundle was saved Default=null Max Length=255

password                  Password of the user required to obtain the token. This is required only by Set and Add

### ExecuteSet Collection

Set one or more field values for a Collection.

parameters                  Parameters needed to identify the record to be changed.

This required

collectionId              GUID of the Collection to Set.

or this required & resolution

collectionName            Name of the Collection to Set.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

record                      Record containing the new values for fields to be changed.

collectionName            Name of the Collection. It is unique within the Site. Max Length=50

description               User description. Default="" Max Length=250

templateDeviceId          GUID of a Device in the Collection whose settings are used for initial values of new Devices. Not used with templateDeviceName. Default=null Length=36

templateDeviceName        Name of a Device in the Collection whose settings are used for initial values of new Devices. Not used with templateDeviceId. Default=null

lastAutoAddDeviceNumber   The Device Number of the last Auto Added Device. Default=0

enabled                   1 when Devices in the Collection can be booted, 0 otherwise. Default=1

autoAddPrefix             The string put before the Device Number for Auto Add. Default=null ASCII computer name characters no end digit Max Length=12

autoAddSuffix             The string put after the Device Number for Auto Add. Default=null ASCII computer name characters no begin digit Max Length=12

autoAddZeroFill           1 when zeros be placed before the Device Number up to the autoAddNumberLength for Auto Add, 0 otherwise. Default=1

autoAddNumberLength       The maximum length of the Device Number for Auto Add. This length plus the autoAddPrefix length plus the autoAddSuffix length must be less than 16. Required that ((lenautoAddPrefix+lenautoAddSuffix)+autoAddNumberLength)<=15. Min=3, Max=9, Default=4

### ExecuteSet Device

Set one or more field values for one or more Devices.

parameters                  Parameters needed to identify the record to be changed.

One of these required

deviceId                  GUID of the Device to Set.

deviceName                Name of the Device to Set.

deviceMac                 MAC of the Device to Set.

collectionId              GUID of the Collection to set all Devices. deviceName and deviceMac cannot be set.

siteViewId                GUID of the Site View to set all Devices. deviceName and deviceMac cannot be set.

farmViewId                GUID of the Farm View to set all Devices. deviceName and deviceMac cannot be set.

farmViewName              Name of the Farm View to set all Devices. deviceName and deviceMac cannot be set.

or one of these required & resolutions

collectionName            Name of the Collection to set all Devices. deviceName and deviceMac cannot be set.

siteViewName              Name of the Site View to set all Devices. deviceName and deviceMac cannot be set.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

record                      Record containing the new values for fields to be changed.

deviceName                Computer name with no spaces. ASCII computer name characters Max Length=15

description               User description. Default="" Max Length=250

deviceMac                 Ethernet address as a string in the form XX-XX-XX-XX-XX-XX. Uniquely identifies the Device. Length=17

bootFrom                  Device to boot from. Choices are 1 for vDisk, 2 for Hard Disk, and 3 for Floppy. This cannot be Set for a Device with Personal vDisk. Min=1, Max=3, Default=1

className                 Used by Automatic Update feature to match new versions of Disks to a Device. This cannot be Set for a Device with Personal vDisk. Default="" Max Length=41

port                      UDP port to use with Stream Service. Min=1025, Max=65534, Default=6901

enabled                   1 when it can be booted, 0 otherwise. This cannot be Set for a Device with Personal vDisk. Default=1

localDiskEnabled          If there is a local disk menu choice for the Device, this is 1. This cannot be Set for a Device with Personal vDisk. Default=0

authentication            Device log in authentication. Choices are 0 for none, 1 for User Name/Password, and 2 for Extern. This cannot be Set for a Device with Personal vDisk. Min=0, Max=2, Default=0

user                      Name of user to authenticate before the boot process continues. This cannot be Set for a Device with Personal vDisk. Default="" ASCII Max Length=20

password                  Password of user to authenticate before the boot process continues. This cannot be Set for a Device with Personal vDisk. Default="" ASCII Max Length=100

adTimestamp               The time the Active Directory machine account password was generated. Do not set this field, it is only set internally by PVS. Default=0

adSignature               The signature of the Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default=0

adPassword                The Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default="" ASCII Max Length=256

logLevel                  Level to perform logging at. Values are: 0 (None), 1 (Fatal), 2 (Error), 3 (Warning), 4 (Info), 5 (Debug), and 6 (Trace). Min=0, Max=6, Default=0

domainName                Fully qualified name of the domain that the Device belongs to. Do not set this field, it is only set internally by PVS. Default=null Max Length=255

domainObjectSID           The value of the objectSID AD attribute of the same name for the Device's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=186

domainControllerName      The name of the DC used to create the host's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=4000

domainTimeCreated         The time that the computer account was created. Do not set this field, it is only set internally by PVS. Format is: YYYY-MM-DD HH:MM:SS.SSS Default=null

type                      1 when it performs test of Disks, 2 when it performs maintenance on Disks, 3 when it has a Personal vDisk, 4 when it has a Personal vDisk and performs tests, 0 otherwise. A Device with type 0 - 3 can only be Set to 0 - 3, and a Device with type 3 - 4 can only be Set to 3 - 4. Min=0, Max=4, Default=0

localWriteCacheDiskSize   The size in GB to format the Device cache file disk. If the value is 0, then the disk is not formatted. Min=0, Max=2048, Default=0

bdmBoot                   Use PXE boot when set to 0, BDM boot when set to 1. Default is PXE Default=0

bdmType                   Use PXE boot when set to 0, BDM (Bios) boot when set to 1 and BDM (Uefi) boot when set to 2.  Default=0

bdmFormat                 1 use VHD for BDMboot, 2 use ISO, 3 use USB. Default=0

bdmUpdated                Timestamp of the last BDM boot disk update. Default=null

bdmCreated                Timstamp when BDM device was created  Default=null

xsPvsProxyUuid            UUID of XenServer PVS\_proxy Default=null Length=36

enableXsProxy             Enable XenServerProxy when set to 1 Default=null

### ExecuteSet Disk

Set one or more field values for a Disk.

parameters                  Parameters needed to identify the record to be changed.

This required

diskLocatorId             GUID of the Disk Locator.

or this required & resolution

diskLocatorName           Name of the Disk Locator.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

record                      Record containing the new values for fields to be changed.

class                     Class of the Disk. Max Length=40

imageType                 Type of this image (software type). Max Length=40

writeCacheSize            RAM cache size (MB). Not 0 when used with Cache in Device RAM, and Cache in Device RAM with Overflow on Hard Disk. A value of 0 will disable the RAM use for Cache in Device RAM with Overflow on Hard Disk. Min=0, Max=131072, Default=0

autoUpdateEnabled         Automatically update this image for matching Devices when set to 1. Default 0

activationDateEnabled     Use activation date to activate image when set to 1. Default 0

adPasswordEnabled         Enable AD password management when set to 1.

haEnabled                 Enable HA when set to 1.

printerManagementEnabled  Invalid printers will be deleted from the Device when set to 1.

writeCacheType            0 (Private), 1 (Cache on Server), 3 (Cache in Device RAM), 4 (Cache on Device Hard Disk), 7 (Cache on Server, Persistent), 9 (Cache in Device RAM with Overflow on Hard Disk), 10 (Private async), 11(Server persistent async), 12 (Cache in Device RAM with Overflow on Hard Disk async) Min=0, Max=12, Default=0

licenseMode               0 (None), 1 (Multiple Activation Key), or 2 (Key Management Service). Min=0, Max=2, Default=0

accelerateOfficeActivation  Run script to activate office automatically.

activeDate                Date to activate the disk if autoUpdateEnabled and activationDateEnabled are 1. Format is yyyy/mm/dd. Empty when the autoUpdateEnabled or activationDateEnabled are 0.

longDescription           Description of the Disk. Max Length=399

operatingSystem           Operating System of Disk. Max Length=250

osType                    Operating System Type of Disk. Max Length=40

serialNumber              User defined serial number. Max Length=36

date                      User defined date. Max Length=40

author                    User defined author. Max Length=40

title                     User defined title. Max Length=40

company                   User defined company. Max Length=40

internalName              User defined name. Max Length=63

originalFile              User defined original file. Max Length=127

hardwareTarget            User defined hardware target. Max Length=127

majorRelease              User defined major release number. Min=0, Max=4294967295, Default=0

minorRelease              User defined minor release number. Min=0, Max=4294967295, Default=0

build                     User defined build number. Min=0, Max=4294967295, Default=0

clearCacheDisabled        Clear cached secrets disabled.

format                    Format of the image. Values are: 0 (VHD), 1 (VHDX). Default=0

### ExecuteSet DiskLocator

Set one or more field values for a Disk Locator.

parameters                  Parameters needed to identify the record to be changed.

This required

diskLocatorId             GUID of the Disk Locator to Set.

or this required & resolution

diskLocatorName           Name of the Disk Locator File to Set.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

record                      Record containing the new values for fields to be changed.

description               User description. Default="" Max Length=250

menuText                  Text that is displayed in the Boot Menu. If this field has no value, the name value is used. Default="" ASCII Max Length=64

serverId                  GUID of the single Server that this Disk Locator is assigned to. It is not used with serverName. Default=null Length=36

serverName                Name of the single Server that this Disk Locator is assigned to. It is not used with serverId. Default=null

enabled                   1 when this disk can be booted, 0 otherwise. Default=1

rebalanceEnabled          1 when this Server can automatically rebalance Devices, 0 otherwise. Default=0

rebalanceTriggerPercent   Percent over fair load that triggers a dynamic Device rebalance. Min=5, Max=5000, Default=25

subnetAffinity            Qualifier for subnet affinity when assigning a Server. 0=None, 1=Best Effort, 2=Fixed. Min=0, Max=2, Default=0

### ExecuteSet DiskUpdateDevice

Set one or more field values for one or more Disk Update Devices.

parameters                  Parameters needed to identify the record to be changed.

One of these required

deviceId                  GUID of the Disk Update Device to Set.

deviceName                Name of Disk Update Device to Set.

deviceMac                 MAC of Disk Update Device to Set.

siteId                    GUID of the Site. Can be used alone to Set all Disk Update Devices in the Site.

siteName                  Name of the Site. Can be used alone to Set all Disk Update Devices in the Site.

diskLocatorId             GUID of the DiskLocator to Set the Disk Update Device for.

or this required & resolution

diskLocatorName           Name of the DiskLocator to Set the Disk Update Device for.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

record                      Record containing the new values for fields to be changed.

description               User description. Default="" Max Length=250

port                      UDP port to use with Stream Service. Min=1025, Max=65534, Default=6901

adTimestamp               The time the Active Directory machine account password was generated. Do not set this field, it is only set internally by PVS. Default=0

adSignature               The signature of the Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default=0

logLevel                  Level to perform logging at. Values are: 0 (None), 1 (Fatal), 2 (Error), 3 (Warning), 4 (Info), 5 (Debug), and 6 (Trace). Min=0, Max=6, Default=0

domainName                Fully qualified name of the domain that the Device belongs to. Do not set this field, it is only set internally by PVS. Default=null Max Length=255

domainObjectSID           The value of the objectSID AD attribute of the same name for the Device's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=186

domainControllerName      The name of the DC used to create the host's computer account. Do not set this field, it is only set internally by PVS. Default=null Max Length=4000

domainTimeCreated         The time that the computer account was created. Do not set this field, it is only set internally by PVS. Format is: YYYY-MM-DD HH:MM:SS.SSS Default=null

adPassword                The Active Directory machine account password. Do not set this field, it is only set internally by PVS. Default="" Max Length=256

### ExecuteSet DiskVersion

Set one or more field values for one Disk Version.

parameters                  Parameters needed to identify the record to be changed.

This required

diskLocatorId             GUID of the Disk Locator Version to Set.

or this required & resolution

diskLocatorName           Name of the Disk Locator Version to Set.

This required

version                   Version to Set.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

record                      Record containing the new values for fields to be changed.

description               User description. Default="" Max Length=250

scheduledDate             Date/Time that the Disk Version is scheduled to become available. Format is: YYYY-MM-DD HH:MM. When empty, the disk version is made available immediately. Default=null

### ExecuteSet Farm

Set one or more field values for a Farm.

parameters                  Parameters needed to identify the record to be changed.

Optional

farmId                    GUID of the Farm to Set. This is optional since there is only one Farm.

record                      Record containing the new values for fields to be changed.

farmName                  Name of the Farm. Default="" Max Length=50

description               User description. Default="" Max Length=250

autoAddEnabled            1 when Auto Add is enabled, 0 otherwise. Default=0

auditingEnabled           1 when Auditing is enabled, 0 otherwise. Default=0

lastAuditArchiveDate      Last date of Audit Trail data that was Archived. Format is yyyy/mm/dd Default=null

defaultSiteId             GUID of the Site to place new Devices into automatically. Not used with defaultSiteName. Default=null Length=36

defaultSiteName           Name of the Site to place new Devices into automatically. Not used with defaultSiteId. Default=null

offlineDatabaseSupportEnabled  1 when Offline Database Support is enabled, 0 otherwise. Default=0

licenseServer             License server name. Default="" Max Length=255

licenseServerPort         License server port. Min=1025, Max=65534, Default=27000

licenseTradeUp            License server trade up, when set to 1. Default=0

licenseSKU                licenseSKU. 0 for on-premises, 1 for cloud. Min=0, Max=1, Default=0

automaticMergeEnabled     1 when Automatic Merge is enabled, 0 otherwise. If the number of versions becomes more than the maxVersions value, a merge will occur at the end of PromoteDiskVersion. Default=1

maxVersions               Maximum number a versions of a Disk that can exist before a merge will automatically occur. Min=3, Max=50, Default=5

mergeMode                 Mode to place the version in after a merge has occurred. Values are: 0 (Production), 1 (Test) and 2 (Maintenance). Min=0, Max=2, Default=2

### ExecuteSet FarmView

Set one or more field values for a Farm View.

parameters                  Parameters needed to identify the record to be changed.

One of these required

farmViewId                GUID of the Farm View to Set.

farmViewName              Name of the Farm View to Set.

record                      Record containing the new values for fields to be changed.

farmViewName              name of the Farm View. Max Length=50

description               User description. Default="" Max Length=250

### ExecuteSet Server

Set one or more field values for a Server. Restart the Stream Service after setting the fields.

parameters                  Parameters needed to identify the record to be changed.

One of these required

serverId                  GUID of the Server to Set.

serverName                Name of the Server to Set.

record                      Record containing the new values for fields to be changed.

serverName                Computer name with no spaces. ASCII computer name characters Max Length=21

description               User description. Default="" Max Length=250

adMaxPasswordAge          Number of days before a password expires. Min=1, Max=30, Default=7

licenseTimeout            Amount of seconds before a license times out. Min=15, Max=300, Default=30

vDiskCreatePacing         VDisk create time pacing in milliseconds. Min=0, Max=5, Default=0

firstPort                 Number of the first UDP port for use by the Stream Service, First and Last must allow at least 5 ports. Min=1025, Max=65534, Default=6910

lastPort                  Number of the last UDP port for use by the Stream Service, First and Last must allow at least 5 ports. Min=1025, Max=65534, Default=6930

threadsPerPort            Number of worker threads per IO port. Required that (threadPerPort \* numberPorts \* numberIPs) <= 1000. Min=1, Max=60, Default=8

buffersPerThread          Number of buffers per worker thread. Min=1, Max=128, Default=24

serverCacheTimeout        Number of seconds to wait before considering another Server is down. Min=5, Max=60, Default=8

ioBurstSize               Number of bytes read/writes can send in a burst of packets. Required that ioBurstSize/(maxTransmissionUnits-76)<=32. Min=4096, Max=61440, Default=32768

maxTransmissionUnits      Ethernet maximum transmission unit size for the protocol for use for Server and Device. Required that ioBurstSize/(maxTransmissionUnits-76)<=32. Min=502, Max=16426, Default=1506

maxBootDevicesAllowed     Maximum number of Devices allowed to boot simultaneously. Min=1, Max=1000, Default=500

maxBootSeconds            Maximum number of seconds for a Device to boot. Min=10, Max=900, Default=60

bootPauseSeconds          Number of seconds that a Device will pause during login if its server busy. Min=1, Max=60, Default=10

adMaxPasswordAgeEnabled   Age the password, when set to 1. Default=0

eventLoggingEnabled       Enable event logging, when set to 1. Default=0

nonBlockingIoEnabled      Use non-Blocking IO, when set to 1. Default=1

ip                        One or more streaming ip addresses. If more than one ip is included, the ip addresses are comma delimited.

initialQueryConnectionPoolSize  Initial size of database connection pool for non-transactional queries. Min=1, Max=1000, Default=50

initialTransactionConnectionPoolSize  Initial size of database connection pool for transactional queries. Min=1, Max=1000, Default=50

maxQueryConnectionPoolSize  Maximum size of database connection pool for non-transactional queries. Min=1, Max=32767, Default=1000

maxTransactionConnectionPoolSize  Maximum size of database connection pool for transactional queries. Min=1, Max=32767, Default=1000

refreshInterval           Interval, in number of seconds, the server should wait before refreshing settings. If set to 0, unused database connections are never released. Min=0, Max=32767, Default=300

unusedDbConnectionTimeout  Interval, in number of seconds, a connection should go unused before it is to be released. Min=0, Max=32767, Default=300

busyDbConnectionRetryCount  Number of times a failed database connection will be retried. Min=0, Max=32767, Default=2

busyDbConnectionRetryInterval  Interval, in number of milliseconds, the server should wait before retrying to connect to a database. Min=0, Max=10000, Default=25

localConcurrentIoLimit    Maximum concurrent IO transactions it performs for vDisks that are local. A value of 0 disables the feature. Min=0, Max=128, Default=4

remoteConcurrentIoLimit   Maximum concurrent IO transactions it performs for vDisks that are remote. A value of 0 disables the feature. Min=0, Max=128, Default=4

logLevel                  Level to perform logging at. Values are: 0 (None), 1 (Fatal), 2 (Error), 3 (Warning), 4 (Info), 5 (Debug), and 6 (Trace). Min=0, Max=6, Default=4

logFileSizeMax            Maximum size log files can reach in Megabytes. Min=1, Max=50, Default=5

logFileBackupCopiesMax    Maximum number of log file backups. Min=1, Max=50, Default=4

powerRating               A strictly relative rating of this Server's capabilities when compared to other Servers in the Store(s) it belongs too; can be used to help tune load balancing. Min=0.1, Max=1000, Default=1

lastCeipUploadAttempt     Time that this server last attempted a CEIP upload. Default=null

lastBugReportAttempt      Time that this server last attempted to upload or generate a bug report bundle. Default=null

lastBugReportStatus       Status of the last bug report on this server. Default=null Max Length=250

lastBugReportResult       Status of the last bug report on this server. Default=null Max Length=4000

lastBugReportSummary      Summary of the last bug report on this server. Default=null Max Length=250

### ExecuteSet ServerBiosBootstrap

Oem Only: Set the bootstrap fields for the Server dell\_bios.bin BIOS bootstrap file.

parameters                  Parameters needed to identify the record to be changed.

One of these required

serverId                  GUID of the Server to Set the dell\_bios.bin BIOS bootstrap file.

serverName                Name of the Server to Set the dell\_bios.bin BIOS bootstrap file.

record                      Record containing the new values for fields to be changed.

enabled                   Automatically update the BIOS on the target device with these setting when set to 1, otherwise do not use these settings. Default=0

dhcpEnabled               Use DHCP to retrieve target device IP when set to 1, otherwise use the static domain, dnsIpAddress1 and dnsIpAddress2 settings. Default=1

lookup                    Use DNS to find the Server when set to 1 with the serverName host value, otherwise use the bootserver1\_Ip, bootserver1\_Port, bootserver2\_Ip, bootserver2\_Port, bootserver3\_Ip, bootserver3\_Port, bootserver4\_Ip, and bootserver4\_Port settings. Default=1

verboseMode               Display verbose diagnostic information when set to 1. Default=0

interruptSafeMode         Interrupt safe mode (use if target device hangs during boot) when set to 1. Default=0

paeMode                   PAE mode (use if PAE enabled in boot.ini of target device) when set to 1. Default=0

bootFromHdOnFail          For network recovery reboot to hard drive when set to 1, restore network connection when set to 0. Default=0

recoveryTime              When bootFromHdOnFail is 1, this is the number of seconds to wait before reboot to hard drive. Min=10, Max=60000, Default=50

pollingTimeout            Login polling timeout in milliseconds. Min=1000, Max=60000, Default=5000

generalTimeout            Login general timeout in milliseconds. Min=1000, Max=60000, Default=5000

serverName                Host to use for DNS lookup. Only used when lookup is 1. Default=IMAGESERVER1

bootserver1\_Ip            1st boot server IP. Only used when lookup is 0.

bootserver1\_Port          1st boot server port. Only used when lookup is 0. Min=1025, Max=65536, Default=6910

bootserver2\_Ip            2nd boot server IP. Only used when lookup is 0. Default=0.0.0.0

bootserver2\_Port          2nd boot server port. Only used when lookup is 0. Min=1025, Max=65536, Default=6910

bootserver3\_Ip            3rd boot server IP. Only used when lookup is 0. Default=0.0.0.0

bootserver3\_Port          3rd boot server port. Only used when lookup is 0. Min=1025, Max=65536, Default=6910

bootserver4\_Ip            4th boot server IP. Only used when lookup is 0. Default=0.0.0.0

bootserver4\_Port          4th boot server port. Only used when lookup is 0. Min=1025, Max=65536, Default=6910

domain                    Domain of the primary and secondary DNS servers. Only used when dhcpEnabled is 0.

dnsIpAddress1             Primary DNS server IP. Only used when dhcpEnabled is 0.

dnsIpAddress2             Secondary DNS server IP. Only used when dhcpEnabled is 0.

### ExecuteSet ServerBootstrap

Set the bootstrap fields for the Server and named bootstrap file specified.

parameters                  Parameters needed to identify the record to be changed.

One of these required

serverId                  GUID of the Server to Set the named bootstrap file on.

serverName                Name of the Server to Set the named bootstrap file on.

This required

name                      Name of the bootstrap file.

record                      Record containing the new values for fields to be changed.

bootserver1\_Ip            1st boot server IP.

bootserver1\_Netmask       1st boot server netmask. Default=0.0.0.0

bootserver1\_Gateway       1st boot server gateway. Default=0.0.0.0

bootserver1\_Port          1st boot server port. Min=1025, Max=65536, Default=6910

bootserver2\_Ip            2nd boot server IP. Default=0.0.0.0

bootserver2\_Netmask       2nd boot server netmask. Default=0.0.0.0

bootserver2\_Gateway       2nd boot server gateway. Default=0.0.0.0

bootserver2\_Port          2nd boot server port. Min=1025, Max=65536, Default=6910

bootserver3\_Ip            3rd boot server IP. Default=0.0.0.0

bootserver3\_Netmask       3rd boot server netmask. Default=0.0.0.0

bootserver3\_Gateway       3rd boot server gateway. Default=0.0.0.0

bootserver3\_Port          3rd boot server port. Min=1025, Max=65536, Default=6910

bootserver4\_Ip            4th boot server IP. Default=0.0.0.0

bootserver4\_Netmask       4th boot server netmask. Default=0.0.0.0

bootserver4\_Gateway       4th boot server gateway. Default=0.0.0.0

bootserver4\_Port          4th boot server port. Min=1025, Max=65536, Default=6910

verboseMode               Display verbose diagnostic information when set to 1. Default=0

interruptSafeMode         Interrupt safe mode (use if target device hangs during boot) when set to 1. Default=0

paeMode                   PAE mode (use if PAE enabled in boot.ini of target device) when set to 1. Default=0

bootFromHdOnFail          For network recovery reboot to hard drive when set to 1, restore network connection when set to 0. Default=0

recoveryTime              When bootFromHdOnFail is 1, this is the number of seconds to wait before reboot to hard drive. Min=10, Max=60000, Default=50

pollingTimeout            Login polling timeout in milliseconds. Min=1000, Max=60000, Default=5000

generalTimeout            Login general timeout in milliseconds. Min=1000, Max=60000, Default=5000

### ExecuteSet ServerStore

Set the directory path and cache paths of a Server for a Store.

parameters                  Parameters needed to identify the record to be changed.

One of these required

serverId                  GUID of a Server that uses the path to get to the Store.

serverName                Name of a Server that uses the path to get to the Store.

One of these required

storeId                   GUID of the Store.

storeName                 Name of the Store.

record                      Record containing the new values for fields to be changed.

path                      Directory path that the Server uses to access the Store. Default="" Max Length=255

cachePath                 Cache path(s) that the Server uses with the Store. It is an ordered comma-delimited list. If none are specified the caches will be placed in the Store cachePath. Default=None

### ExecuteSet Site

Set one or more field values for a Site.

parameters                  Parameters needed to identify the record to be changed.

One of these required

siteId                    GUID of the Site to Set.

siteName                  Name of the Site to Set.

record                      Record containing the new values for fields to be changed.

siteName                  Name of the Site. Max Length=50

description               User description. Default="" Max Length=250

defaultCollectionId       GUID of the Collection to place new Devices into automatically. Not used with defaultCollectionName. Default=null Length=36

defaultCollectionName     Name of the Collection to place new Devices into automatically. Not used with defaultCollectionId. Default=null

inventoryFilePollingInterval  The number of seconds between polls for Disk changes in the Stores. Min=1, Max=600, Default=60

enableDiskUpdate          1 when Disk Updated is enabled for the Site, 0 otherwise. Default=0

diskUpdateServerId        GUID of the Disk Update Server for the Site. Not used with diskUpdateServerName. Default=null Length=36

diskUpdateServerName      Name of the Disk Update Server for the Site. Not used with diskUpdateServerId. Default=null

makUser                   User name used for MAK activation. Default=null Max Length=64

makPassword               User password used for MAK activation. Default=null Max Length=64

enableXsProxy             Enable XenServerProxy when set to 1 Default=null

virtualHostingPoolId      GUID of the VirtualHostingPool object.

virtualHostingPoolName    Name of the VirtualHostingPool object.

xsPvsSiteUuid             GUID of the XenServer PVS Site.

### ExecuteSet SiteView

Set one or more field values for a Site View.

parameters                  Parameters needed to identify the record to be changed.

This required

siteViewId                GUID of the Site View to Set.

or this required & resolution

siteViewName              Name of the Site View to Set.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

record                      Record containing the new values for fields to be changed.

siteViewName              Name of the Site View. Max Length=50

description               User description. Default="" Max Length=250

### ExecuteSet Store

Set one or more field values for a Store.

parameters                  Parameters needed to identify the record to be changed.

One of these required

storeId                   GUID of the Store to Set.

storeName                 Name of the Store to Set.

record                      Record containing the new values for fields to be changed.

storeName                 Name of the Store. Max Length=50

siteId                    GUID of the Site where Administrators of that Site can change this Store. Not used for Farm Stores. siteName can be used instead. Default=null Length=36

siteName                  Name of the Site where Administrators of that Site can change this Store. Not used for Farm Stores. siteId can be used instead. Default=null

description               User description. Default="" Max Length=250

path                      Default directory path that the Servers use to access this Store. Max Length=255

cachePath                 Default Cache path(s) that the Servers use with this Store. It is an ordered comma-delimited list. If none are specified the caches will be placed in the WriteCache subdirectory of the Store path. Default=None

### ExecuteSet UpdateTask

Set one or more field values for an Update Task.

parameters                  Parameters needed to identify the record to be changed.

This required

updateTaskId              GUID of the Update Task to Set.

or this required & resolution

updateTaskName            Name of the Update Task to Set.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

record                      Record containing the new values for fields to be changed.

updateTaskName            Name of the Update Task. It is unique within the Site. Max Length=50

description               User description. Default="" Max Length=250

enabled                   1 when it will be processed, 0 otherwise. Default=1

hour                      The hour of the day to perform the task. Min=0, Max=23, Default=0

minute                    The minute of the hour to perform the task. Min=0, Max=59, Default=0

recurrence                The update will reoccur on this schedule. 0 = None, 1 = Daily, 2 = Every Weekday, 3 = Weekly, 4 = Monthly Date, 5 = Monthly Type. Min=0, Max=5, Default=0

dayMask                   Days selected values. 1 = Monday, 2 = Tuesday, 4 = Wednesday, 8 = Thursday, 16 = Friday, 32 = Saturday, 64 = Sunday, 128 = Day. Default=0. This is used with Weekly and Monthly Type recurrence. Min=1, Max=255, Default=4

date                      Comma delimited days of the month. Numbers from 1-31 are the only valid values. This is used with Monthly Date recurrence. Default="" Max Length=83

monthlyOffset             When to happen monthly. 0 = None, 1 = First, 2 = Second, 3 = Third, 4 = Forth, 5 = Last. This is used with Monthly Type recurrence. Min=0, Max=5, Default=3

esdType                   Esd to use. Valid values are SCCM or WSUS. If no value, a custom script is run on the client. Default=null Max Length=50

preUpdateScript           Script file to run before the update starts. Default=null Max Length=255

preVmScript               Script file to run before the VM is loaded. Default=null Max Length=255

postUpdateScript          Script file to run after the update finishes. Default=null Max Length=255

postVmScript              Script file to run after the VM is unloaded. Default=null Max Length=255

domain                    Domain to add the Disk Update Device(s) to. If not included, the first Domain Controller found on the Server is used. Default=null Max Length=255

organizationUnit          Organizational Unit to add the Disk Update Device(s) to. This parameter is optional. If it is not specified, the device is added to the built in Computers container. Child OU's should be delimited with forward slashes, e.g. "ParentOU/ChildOU". Special characters in an OU name, such as '"', '#', '+', ',', ';', '>', '=', must be escaped with a backslash. For example, an OU called "commaIn,TheMiddle" must be specified as "commaIn\\,TheMiddle". The old syntax of delimiting child OU's with a comma is still supported, but deprecated. Note that in this case, the child OU comes first, e.g. "ChildOU,ParentOU". Default=null Max Length=255

postUpdateApprove         Access to place the version in after the update has occurred. 0 = Production, 1 = Test, 2 = Maintenance. Min=0, Max=2, Default=0

### ExecuteSet VirtualHostingPool

Set one or more field values for a Virtual Hosting Pool.

parameters                  Parameters needed to identify the record to be changed.

This required

virtualHostingPoolId      GUID of the Virtual Hosting Pool to Set.

or this required & resolution

virtualHostingPoolName    Name of the Virtual Hosting Pool to Set.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

record                      Record containing the new values for fields to be changed.

virtualHostingPoolName    Name of the Virtual Hosting Pool. It is unique within the Site. Max Length=50

type                      Type of the Virtual Hosting Pool. 0 = Citrix XenServer, 1 = Microsoft SCVMM/Hyper-V, 2 = VMWare vSphere/ESX. Min=0, Max=3, Default=0

description               User description. Default="" Max Length=250

server                    Name or IP of the Host Server. Max Length=255

port                      Port of the Host Server. Min=80, Max=65534, Default=80

datacenter                Datacenter of the Virtual Hosting Pool. Default="" Max Length=250

updateLimit               Number of updates at the same time. Min=2, Max=1000, Default=1000

updateTimeout             Timeout for updates. Min=2, Max=240, Default=60

shutdownTimeout           Timeout for shutdown. Min=2, Max=30, Default=10

userName                  Name to use when logging into the Server.

password                  Password to use when logging into the Server.

xdHostingUnitUuid         UUID of XenDesktop Hosting Unit Default=null Length=36

prepopulateEnabled        Enable prepopulate when set to 1 Default=0

xsPvsSiteUuid             UUID of XenServer PVS\_site  Default=null Length=36

platformVersion            Hypervisor Host Version  Default=null Max Length=250

xdHcHypervisorConnectionName  Hypervisor Connection Name for HCL Connection Details object Default=null Max Length=250

xdHcHypervisorConnectionUid  Hypervisor Connection Uid for HCL Connection Details object Default=null Max Length=250

xdHcRevision              Revision for HCL Connection Details object Default=null Max Length=250

xdHcCustomProperties      Custom Properties for HCL Connection Details object Default=null Max Length=250

xdHcSslThumbprints        Ssl Thumbprints for HCL Connection Details object Default=null Max Length=250

disableHostXsProxy        True to disable PVS-Accelerator Default=null

### ExecuteSet VirtualHostingPoolServer

parameters                  Parameters needed to identify the record to be changed.

This required

virtualHostingPoolId      GUID of the Virtual Hosting Pool to Set.

This required

serverId                  GUID of the Server to Set.

record                      Record containing the new values for fields to be changed.

virtualHostingPoolId      GUID of the Virtual Hosting Pool being used for XenServer PVS proxy. Length=36

serverId                  GUID of the Server that has a PVS\_server in XenServer Length=36

xsPvsServerUuid           UUID of the XenServer PVS\_server Length=36

### ExecuteSet XDSite

Set the configServices field value for a XenDesktop Site.

parameters                  Parameters needed to identify the record to be changed.

This required

xdSiteId                  GUID of the XenDesktop Site to Set.

record                      Record containing the new values for fields to be changed.

configServices            Comma delimited list of XenDesktop Server addresses. Max Length=2000

## ExecuteSetList

MapiReturn ExecuteSetList(string command,

List<KeyValuePair<string, string>> parameters,

List<List<KeyValuePair<string, string>>> records);

### ExecuteSetList DeviceBootstraps

Set the Bootstrap Files for a Device.

parameters                  Parameters needed to identify the record to be changed.

One of these required

deviceId                  GUID of the Device.

deviceName                Name of the Device.

deviceMac                 MAC of the Device.

records                     Records with fields to set.

bootstrap                 Name of the bootstrap file. Max Length=259

menuText                  Text that is displayed in the Boot Menu. If this field has no value, the bootstrap value is used. Default="" ASCII Max Length=64

### ExecuteSetList DeviceCustomProperty

Set the Device Custom Property names and values.

parameters                  Parameters needed to identify the record to be changed.

One of these required

deviceId                  GUID of the Device.

deviceName                Name of the Device.

deviceMac                 MAC of the Device.

records                     Records with fields to set.

name                      Name of the Device custom property. Max Length=250

value                     Value of the Device custom property. Max Length=1000

### ExecuteSetList DeviceDiskPrinters

Set one or more Printer settings. Only the changed items need to be passed. To remove a Printer, set it as disabled.

parameters                  Parameters needed to identify the record to be changed.

One of these required

deviceId                  GUID of the Device.

deviceName                Name of the Device.

deviceMac                 MAC of the Device.

This required

diskLocatorId             GUID of the Disk Locator.

or this required & resolution

diskLocatorName           Name of the Disk Locator File.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

records                     Records with fields to set.

name                      Name of the Printer. Must come from the list of Printers available on the Disk.

state                     Valid states are 1 (enabled network), 2 (enabled local), or 3 (default). 0 (disabled) can be used when setting a Printer that used to be 1 or 2 to 0. The list of all Printers available come from the Disk. Min=0, Max=3

### ExecuteSetList DevicePersonality

Set the Device Personality names and values.

parameters                  Parameters needed to identify the record to be changed.

One of these required

deviceId            nbsp;      GUID of the Device.

deviceName                Name of the Device.

deviceMac                 MAC of the Device.

records                     Records with fields to set.

name                      Name of the Device personality item. Max Length=250

value                     Value for the Device personality item. Max Length=1000

### ExecuteSetList DiskLocatorCustomProperty

Set the DiskLocator Custom Property names and values.

parameters                  Parameters needed to identify the record to be changed.

This required

diskLocatorId             GUID of the Disk Locator.

or this required & resolution

diskLocatorName           Name of the Disk Locator.

One of these resolutions when needed

siteId                    GUID of the Site.

siteName                  Name of the Site.

One of these resolutions when needed

storeId                   GUID of the Store that is needed when a diskLocatorName is used.

storeName                 Name of the Store that is needed when a diskLocatorName is used.

records                     Records with fields to set.

name                      Name of the DiskLocator custom property. Max Length=250

value                     Value of the DiskLocator custom property. Max Length=1000

### ExecuteSetList ServerCustomProperty

Set the Server Custom Property names and values.

parameters                  Parameters needed to identify the record to be changed.

One of these required

serverId                  GUID of the Server.

serverName                Name of the Server.

records                     Records with fields to set.

name                      Name of the Server custom property. Max Length=250

value                     Value of the Server custom property. Max Length=1000