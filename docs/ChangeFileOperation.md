
# ChangeFileOperation

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**content** | **String** | new or updated file content, it must be base64 encoded |  [optional]
**fromPath** | **String** | old path of the file to move |  [optional]
**operation** | [**OperationEnum**](#OperationEnum) | indicates what to do with the file: \&quot;create\&quot; for creating a new file, \&quot;update\&quot; for updating an existing file, \&quot;upload\&quot; for creating or updating a file, \&quot;rename\&quot; for renaming a file, and \&quot;delete\&quot; for deleting an existing file. | 
**path** | **String** | path to the existing or new file | 
**sha** | **String** | the blob ID (SHA) for the file that already exists, required for changing existing files |  [optional]


<a name="OperationEnum"></a>
## Enum: OperationEnum
Name | Value
---- | -----
CREATE | &quot;create&quot;
UPDATE | &quot;update&quot;
UPLOAD | &quot;upload&quot;
RENAME | &quot;rename&quot;
DELETE | &quot;delete&quot;



