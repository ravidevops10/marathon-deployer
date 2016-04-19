A python script that uses marathon healthchecks to do atomic rolling deployment of apps on Marathon. It follows blue-green deployment model. It ensures that deployment is rolled back if healthcheck fails due to any reason. It is designed to deploy Java application which use Maven. It integrates with Gitlab to pull the latest code changes and adds versioning to the apps. A deployment is triggered whenever there is a code change or marathon config change.
