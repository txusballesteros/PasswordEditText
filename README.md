Password EditText
=================

![](assets/hiden.png)
![](assets/reveal.png)

Password EditText is the easy way to have a reveal password field into your login screens. Let to your users check if they enter correctly their password. 

## Latest Version

[ ![Download](https://api.bintray.com/packages/txusballesteros/maven/PasswordEditText/images/download.svg) ](https://bintray.com/txusballesteros/maven/PasswordEditText/_latestVersion) ![](https://img.shields.io/badge/platform-android-green.svg) ![](https://img.shields.io/badge/Min%20SDK-1-green.svg) ![](https://img.shields.io/badge/Licence-Apache%20v2-green.svg) [![Build Status](https://travis-ci.org/txusballesteros/PasswordEditText.svg?branch=master)](https://travis-ci.org/txusballesteros/PasswordEditText)

## How to use

### 1.- Configuring your project dependencies

Add the library dependency to your build.gradle file.

```groovy
dependencies {
    ...
    compile 'com.txusballesteros:PasswordEditText:1.0.0'
}
```

### 2.- Adding and Customizing the View

Add the view to your xml layout file.

```xml
<com.txusballesteros.PasswordEditText
        ...
        app:showDrawable="@drawable/ic_password_visible_24dp"
        app:hideDrawable="@drawable/ic_password_hidden_24dp"
        app:drawableTintCompat="?attr/colorAccent"/>
```

### 3.- Enjoy

And at the end, enjoy the library.

## License

Copyright Txus Ballesteros 2016

This file is part of some open source application.

Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.