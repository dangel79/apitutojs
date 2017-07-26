# ApiEssaiSwagger.DefaultApi

All URIs are relative to *https://virtserver.swaggerhub.com/dangeli/essai/V1.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**usersUserIdGet**](DefaultApi.md#usersUserIdGet) | **GET** /users/{userId} | Returns a user by ID


<a name="usersUserIdGet"></a>
# **usersUserIdGet**
> InlineResponse200 usersUserIdGet(userId)

Returns a user by ID

### Example
```javascript
var ApiEssaiSwagger = require('api_essai_swagger');

var apiInstance = new ApiEssaiSwagger.DefaultApi();

var userId = 56; // Number | The ID of the user to return


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
apiInstance.usersUserIdGet(userId, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userId** | **Number**| The ID of the user to return | 

### Return type

[**InlineResponse200**](InlineResponse200.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

