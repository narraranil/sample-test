/*
* Copyright © 2010 - 2013 Apama Ltd.
* Copyright © 2013 - 2018 Software AG, Darmstadt, Germany and/or its licensors
*
* SPDX-License-Identifier: Apache-2.0
*
*   Licensed under the Apache License, Version 2.0 (the "License");
*   you may not use this file except in compliance with the License.
*   You may obtain a copy of the License at
*
*       http://www.apache.org/licenses/LICENSE-2.0
*
*   Unless required by applicable law or agreed to in writing, software
*   distributed under the License is distributed on an "AS IS" BASIS,
*   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
*   See the License for the specific language governing permissions and
*   limitations under the License.                                                            
*
*/

pipeline {
    agent any 

    stages {
	   stage('Clone repository') {
        /* Let's make sure we have the repository cloned to our workspace */

        checkout scm
		}
        stage('Build'){
            steps {
                echo "build successful"
            }
        }
        stage('Deploy') {
            steps {
				echo "deploy successful"
            }
        }
 	stage('Test') {
            steps {
				echo "test successful"
            }
        }
    }
}
