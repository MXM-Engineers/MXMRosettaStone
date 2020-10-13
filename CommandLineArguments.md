# Command Line Arguments
## Know working Command Line Arguments

Used value:
* 1: Official used
* 2: Tested and works
* 3: Not really tested
* 4: Needs testing

| Argument | Value | Info | Used |
|----------|-------|------|---------|
| /AuthMethod="[value]" | ncplatform | Select the authentication method to use: ncplatform = the live ncnetwork | 1 |
|          | local | Disables the need for authentication with the nc network | 2 |
| /Network:"[value]" | dev | doesn’t give Cannot connect to server. Do you want to try again? it try’s to connect on private local ip 172.19.66.197:6600 | 2 |
|          | ncplatform | this give the error(may be invalid value for this parameter) (is invalid) | 3 
|          | live  | same | 3 |
| /ForceCrash | | Crashes the game on launch and triggers ncdiagS64.exe after crash | 2 |
| /Crypto:"[value]" | 1 | launched with launcher region EU | 1 |
| /UseCef  |  | launched with launcher region EU | 1 |
| /AuthnToken:"[value]" |  | launched with launcher region EU | 1 |
| /SessKey:"[value]" |  | launched with launcher region EU | 1 |
| /ServiceRegion:"[value]" | 12 | launched with launcher region EU | 1 |
| /AuthProviderCode:”[value]” | np | launched with launcher region EU | 1 |
| /NPServerAddr:[value]” | 64.25.35.100:6600 | launched with launcher region EU | 1 |
| -lang:[value] | ENU | Set's the in game interface language (english) | 1 |
|          | DEU | deutsch | 2 |
|          | ESP | espagnole | 2 |
|          | FRA | french | 2 |
|          | GLOBAL | english | 2 |
|          | ITA |  | 3 |
|          | POL |  | 3 |
|          | TUR |  | 3 |
| /TextLang:"[value]" | en | launched with launcher region EU | 1 |
| /VoiceLang:"[value]" | en | launched with launcher region EU | 1 |
| -region:[value] | 1 | launched with launcher region EU | 1 |
|          | 0 | launched with launcher region NA | 1 |
| /ServerAddr:"[value]" | 32.185.22.41:10900 | EU game server address | 1 |
|          | 64.25.44.30:10900 | NA game server address | 1 |
| /GameRegion:"[value]" | eu | set game region to Europe | 1 |
|          | na | set game region to North-America | 1 |
| /PresenceId:"[value]" | MXM | launched with launcher region EU | 1 |
| -uianalyzer |  | launches ui debugger | 2 |
| /LogEncryption:[value] | 0 | disable encryption of log file | 2 |
|          | 1 | enable encryption of log file (default) | 3 |
| /UsePakOnly:[value] | 0 | you can overwrite files in pak's with your files | 2 |
| /PacketEncryption:[value] | 0 | [PacketFilter] disabled! in log otherwise it’s [LEAPacketFilter] initialize Start! | 2 |

## Arguments that need more research on how they work
These arguments could need some extra values, need - or / to work
* /Test
* /Locale
* /StageTest
* /SoundLog
* /InHouse
* /StartGameID
* /ServerAddrEx
* /TLMin
* /TLC
* /TLDate
* /AutoLoginID
* /MapRecord
* -record
* -replay
* /SingleModeDifficulty
* -easy            it’s possible that these 5 parameters are values to give to 
* -normal        /SingleModeDifficulty:”easy” (maybe I don’t know)
* -hard
* -extreme
* -hell
* /AITest
* /DisableCharacter
* /Network
* -dev            it’s possible that these 2 parameters are values to give to
* -live            /Network:”dev”
* /MemLogAuto
* /LogEncryption
* /DataDirectory
* /Lang
* /AutoJoinGame
* /UsePakOnly        possible that the game reads from unpacked files
* /HideDebugLayer
* -ngs
* /DisableBlinkCheck
* /RemoveAfkTimer
* MLTrainer
* /ProgramId
* /LogSts
* /HideShopTabDisable
* /UseCefHalf
* /UseCef
* /ExAccessToken
