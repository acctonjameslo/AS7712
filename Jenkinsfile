pipeline {
    agent any
    
    stages {
        stage('Functional Test') {
            
                stage('1QVLAN') {
                                steps {
                                        echo 'Running the Functional Test - 1QVLAN . . .'
                                }
                }
                stage('802.1ag-CFM') {
                                steps {
                                    echo 'Running the Functional Test - 802.1ag-CFM . . .'
                                }
                }
                stage('ACL') {
                                steps {
                                    echo 'Running the Functional Test - ACL . . .'
                                }
                }            
                stage('ACL-Compress') {
                                steps {
                                    echo 'Running the Functional Test - ACL-Compress . . .'
                                }
                }            
                stage('ACL-TimeBased') {
                                steps {
                                    echo 'Running the Functional Test - ACL-TimeBased . . .'
                                }
                }            
        }
        
        stage('Functional Test - Topology_2') {
            steps {
                echo 'Running the Functional Test - Topology_2 . . .'
            }
        }
    }
    
    
} 
