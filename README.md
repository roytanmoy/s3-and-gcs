# S3-and-GCS
Design approach for using MultiCloud services e.g, blob storage on GCP and AWS.

In case of business needs for moving from one cloud to another, the setup code only needs to be platform specific whereas business logic shall be free from underlying infra code.  This is utmost important specifically with time when business logic grows fast and vast into complexities such that initial usages of cloud specific code become tighly coupled with the application and become hinderance for a easy and bug free migration to a new cloud platform. 
