# Alfresco REST API Explorer
Public REST API Definition Explorer

#### Definitions

Please note, as of now:

- the [https://github.com/Alfresco/rest-api-explorer/tree/master/src/main/webapp/definitions](definitions) on the 'master' branch represent Alfresco 4.2 to 5.1.

- the [https://github.com/Alfresco/rest-api-explorer/tree/community-head/src/main/webapp/definitions](definitions) on the 'community-head' branch represent Alfresco Community HEAD (aka nightly builds).

#### Building and deploying the war
- `mvn install`

You now have a `target/api-explorer.war`, drop this into your Application server that is running alfresco.war


#### For development only
You can run the project as a packaged web application using an embedded Tomcat server.  
This is useful for changing documentation and endpoint descriptions but it means that the "Try it Out!" button will not work.

- ` mvn tomcat7:run-war`

Now the application is running at [http://localhost:8085/api-explorer](http://localhost:8085/api-explorer/)

### License
Copyright (C) 2016 Alfresco Software Limited

This file is part of an unsupported extension to Alfresco.

Alfresco Software Limited licenses this file
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