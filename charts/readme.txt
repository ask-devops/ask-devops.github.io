cd charts
helm package ask-nginx-web-app/
helm repo index --url=https://ask-devops.github.io/charts/ .
git add .
git commit -m "version 0.3.0"
git push origin main
 
