# AppFeatureDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [optional] [default to undefined]
**creationTime** | **string** |  | [optional] [default to undefined]
**creatorId** | **string** |  | [optional] [default to undefined]
**lastModificationTime** | **string** |  | [optional] [default to undefined]
**lastModifierId** | **string** |  | [optional] [default to undefined]
**isDeleted** | **boolean** |  | [optional] [default to undefined]
**deleterId** | **string** |  | [optional] [default to undefined]
**deletionTime** | **string** |  | [optional] [default to undefined]
**appId** | **string** | 所属应用ID | [optional] [default to undefined]
**name** | **string** | 功能名称（唯一标识） | [optional] [default to undefined]
**displayName** | **string** | 显示名称（默认语言） | [optional] [default to undefined]
**description** | **string** | 描述（默认语言） | [optional] [default to undefined]
**details** | **string** | 详情（默认语言） | [optional] [default to undefined]
**screenshotKeys** | **string** | 截图键值，多个用逗号分隔 | [optional] [default to undefined]
**displayNameLocalized** | **string** | 多语言显示名称，JSON格式：{\&quot;en\&quot;: \&quot;Feature Name\&quot;, \&quot;zh-Hans\&quot;: \&quot;功能名称\&quot;, ...} | [optional] [default to undefined]
**descriptionLocalized** | **string** | 多语言描述，JSON格式：{\&quot;en\&quot;: \&quot;Description\&quot;, \&quot;zh-Hans\&quot;: \&quot;描述\&quot;, ...} | [optional] [default to undefined]
**detailsLocalized** | **string** | 多语言详情，JSON格式：{\&quot;en\&quot;: \&quot;Details\&quot;, \&quot;zh-Hans\&quot;: \&quot;详情\&quot;, ...} | [optional] [default to undefined]

## Example

```typescript
import { AppFeatureDto } from 'puupee-api-axios';

const instance: AppFeatureDto = {
    id,
    creationTime,
    creatorId,
    lastModificationTime,
    lastModifierId,
    isDeleted,
    deleterId,
    deletionTime,
    appId,
    name,
    displayName,
    description,
    details,
    screenshotKeys,
    displayNameLocalized,
    descriptionLocalized,
    detailsLocalized,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
