# Go API client for swagger

This is a mini blog.

## Overview
This API client was generated by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project.  By using the [swagger-spec](https://github.com/swagger-api/swagger-spec) from a remote server, you can easily generate an API client.

- API version: 1.0.0
- Package version: 1.0.0
- Build package: io.swagger.codegen.languages.GoClientCodegen

## Installation
Put the package under your project folder and add the following in import:
```golang
import "./swagger"
```

## Documentation for API Endpoints

All URIs are relative to *http://localhost*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*ArticleApi* | [**AddArticle**](docs/ArticleApi.md#addarticle) | **Post** /api/article/ | Add a new article
*ArticleApi* | [**DeleteArticle**](docs/ArticleApi.md#deletearticle) | **Delete** /api/article/{articleID} | Delete an existing article
*ArticleApi* | [**GetAllArticle**](docs/ArticleApi.md#getallarticle) | **Get** /api/article/ | Get all articles
*ArticleApi* | [**GetArticleByID**](docs/ArticleApi.md#getarticlebyid) | **Get** /api/article/{articleID} | Get article by ID
*ArticleApi* | [**GetArticleByTag**](docs/ArticleApi.md#getarticlebytag) | **Get** /api/article/tag/tag | Get article by Tag
*ArticleApi* | [**GetArticleByUser**](docs/ArticleApi.md#getarticlebyuser) | **Get** /api/article/user/{userID} | Get article by User
*ArticleApi* | [**UpdateArticle**](docs/ArticleApi.md#updatearticle) | **Put** /api/article/{articleID} | Update an existing article
*ReviewApi* | [**CreateReview**](docs/ReviewApi.md#createreview) | **Post** /api/review/{articleID}/{userID} | Submit review
*UserApi* | [**CreateUser**](docs/UserApi.md#createuser) | **Post** /api/user/ | Create user
*UserApi* | [**GetUserbyID**](docs/UserApi.md#getuserbyid) | **Get** /api/user/{userID} | Get user by userid
*UserApi* | [**QueryUser**](docs/UserApi.md#queryuser) | **Get** /api/user/ | Query user
*UserApi* | [**UpdateUser**](docs/UserApi.md#updateuser) | **Put** /api/user/ | Update user


## Documentation For Models

 - [Article](docs/Article.md)
 - [Review](docs/Review.md)
 - [Tag](docs/Tag.md)
 - [User](docs/User.md)


## Documentation For Authorization
 Endpoints do not require authorization.


## Author

chris-ju@qq.com

