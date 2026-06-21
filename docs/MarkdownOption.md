
# MarkdownOption

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**context** | **String** | URL path for rendering issue, media and file links Expected format: /subpath/{user}/{repo}/src/{branch, commit, tag}/{identifier/path}/{file/dir}  in: body |  [optional]
**mode** | **String** | Mode to render (markdown, comment, wiki, file)  in: body |  [optional]
**text** | **String** | Text markdown to render  in: body |  [optional]
**wiki** | **Boolean** | Is it a wiki page? (use mode&#x3D;wiki instead)  Deprecated: true in: body |  [optional]



