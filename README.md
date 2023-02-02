![image](https://user-images.githubusercontent.com/65929678/216216243-440bcb5c-5052-4946-9cad-47a98842e363.png)
# aptoplay-unity-public
The AptoPlay game client engine uses Unity 2021.3.11f1 (LTS).

### Assets list in use
| Name | Range | Link |
| --- | --- | --- |
| PlayFab SDK | PlayFab Development Kit for Unity | https://learn.microsoft.com/ko-kr/gaming/playfab/sdks/unity3d/ |
| RPG Builder | RPG template asset for Unity | https://assetstore.unity.com/packages/tools/game-toolkits/rpg-builder-177657 |

### User sign in

https://user-images.githubusercontent.com/53609504/216229474-a42b32d3-4a10-46be-91a3-395b40845aac.mp4


You can use the PlayFabClientAPI provided by the PlayFab SDK to implement the login feature.

The login feature has been implemented using the LoginWithEmailAddress function. Upon successful login, you can receive the PlayFabId from the result received in the callback, and use it in other APIs as needed. You can refer to the [following page](https://api.playfab.com/Documentation/Client/method/LoginWithEmailAddress) for more information on this function.

### 

### CharacterData Save & Load

https://user-images.githubusercontent.com/53609504/216230578-ac9493bb-cbd7-44ad-9734-50e12cc8bfe2.mp4


In RPG Builder, CharacterData is saved to or loaded from the PlayFab server. The APIs used for saving and loading character data are as follows:

| Name | Description | Link |
| --- | --- | --- |
| Get Player Statistics | Retrieves the current version and values for the indicated statistics, for the local player. | https://learn.microsoft.com/en-us/rest/api/playfab/server/player-data-management/get-player-statistics?view=playfab-rest |
| Update Player Statistics | Updates the values of the specified title-specific statistics for the user. | https://learn.microsoft.com/en-us/rest/api/playfab/client/player-data-management/update-player-statistics?view=playfab-rest |

### RPG Contents

RPG Builder assets are a collection of assets that provide basic elements for building an RPG (Role-Playing Game). These assets can include character models, weapons, environments, and other game assets that are commonly found in RPGs.


