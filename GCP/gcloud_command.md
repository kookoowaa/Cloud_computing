> 기본 리전 및 영역 확인
> 
> ```
> gcloud config get-value compute/zone
> gcloud config get-value compute/region
> 
> gcloud config list compute/zone
> gcloud config list compute/region
> ```
> 
> 기본 리전 및 영역 변경
> 
> ```
> gcloud config set compute/zone
> gcloud config set compute/region 
> ```


> 환경 변수 설정 (linux)
> 
> ```shell
> export PROJECT_ID=<your_project_ID>
> export ZONE=<your_zone>
> 
> 
> echo $PROJECT_ID
> ## <your_project_ID>
> echo $ZONE
> ## <your_zone>
> ```
> 
> 
