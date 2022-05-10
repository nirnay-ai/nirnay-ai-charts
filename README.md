# nirnay-ai-charts
Helm Chart for Installing Nirnay AI Platform 

helm repo add nirnay-ai https://hybridworkforce.github.io/nirnay-ai-charts/

helm install nirnay-ai-platform nirnay-ai/nirnay-ai-platform 


Install Shell Script 

wget https://raw.githubusercontent.com/hybridworkforce/nirnay-ai-charts/main/cli/nirnay-ai
cp nirnay-ai /usr/local/bin/
chmod +x /usr/local/bin/nirnay-ai