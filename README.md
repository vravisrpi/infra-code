# infra-code

### To enable logging in the GCP for the Buckets.###########

gsutil logging set on -b <logging bucket> -o <folder> <bucket URI>
gsutil logging set on -b gs://artifacts.appspot.com/ -o AccessLog_artifcat gs://artifacts.siemens-vision/


