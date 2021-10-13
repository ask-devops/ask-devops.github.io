cd charts
helm package ask-nginx-web-app/
helm repo index --url=https://ask-devops.github.io/charts/ .
git commit -m "version 0.2.0"
git add .
git commit -m "version 0.2.0"
git push origin main
 
