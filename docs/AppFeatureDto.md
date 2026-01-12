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
**name** | **string** | 功能名称（唯一标识，同一功能的不同语言版本使用相同的 Name） | [optional] [default to undefined]
**locale** | **string** | 语言代码（如：en, zh-Hans, zh-Hant, fr 等） | [optional] [default to undefined]
**displayName** | **string** | 显示名称（当前语言） | [optional] [default to undefined]
**description** | **string** | 描述（当前语言） | [optional] [default to undefined]
**details** | **string** | 详情（当前语言） | [optional] [default to undefined]
**screenshotKeys** | **string** | 截图键值，多个用逗号分隔（当前语言的截图） | [optional] [default to undefined]

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
    locale,
    displayName,
    description,
    details,
    screenshotKeys,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
