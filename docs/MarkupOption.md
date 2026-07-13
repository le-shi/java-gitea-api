
# MarkupOption

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**context** | **String** | URL path for rendering issue, media and file links Expected format: /subpath/{user}/{repo}/src/{branch, commit, tag}/{identifier/path}/{file/dir} |  [optional]
**filePath** | **String** | File path for detecting extension in file mode |  [optional]
**mode** | **String** | Mode to render (markdown, comment, wiki, file) |  [optional]
**text** | **String** | Text markup to render |  [optional]
**wiki** | **Boolean** | Is it a wiki page? (use mode&#x3D;wiki instead)  Deprecated: true |  [optional]



