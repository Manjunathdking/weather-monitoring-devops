<!-- DevOps Project - Last Updated: [28-12-2025] -->
\# 🌦️ Smart Climate \& Weather Monitoring System



A real-time weather monitoring dashboard built for DevOps demonstration.



\## 🚀 Features



\- ✅ Real-time weather data from OpenWeatherMap API

\- ✅ Interactive map with click-to-search functionality

\- ✅ Earth time-lapse visualization (1980-2100)

\- ✅ 7-day weather forecast with icons

\- ✅ Drought monitoring with visual gauge

\- ✅ Responsive design for all devices



\## 🛠️ Technologies Used



\### Application Stack

\- \*\*Frontend\*\*: HTML5, CSS3, JavaScript (ES6+)

\- \*\*API\*\*: OpenWeatherMap API

\- \*\*Maps\*\*: Leaflet.js

\- \*\*Styling\*\*: Custom CSS with gradients and animations



\### DevOps Stack

\- \*\*Version Control\*\*: Git, GitHub

\- \*\*Containerization\*\*: Docker

\- \*\*Orchestration\*\*: Kubernetes

\- \*\*CI/CD\*\*: Jenkins / GitHub Actions

\- \*\*Cloud\*\*: AWS / Azure / GCP

\- \*\*Monitoring\*\*: Prometheus, Grafana



\## 📋 Prerequisites



\- Web browser (Chrome, Firefox, Safari, Edge)

\- OpenWeatherMap API key (Get free at: https://openweathermap.org/api)

\- Git installed

\- Docker (optional, for containerization)



\## 🔧 Local Installation



\### Method 1: Direct Browser



1\. Clone the repository:

```bash

git clone https://github.com/yourusername/weather-monitoring-devops.git

cd weather-monitoring-devops

```



2\. Open `index.html` in your browser



\### Method 2: Local Server

```bash

\# Using Python

python -m http.server 8000



\# Using Node.js

npx serve



\# Using PHP

php -S localhost:8000

```



Access at: http://localhost:8000



\## 🌐 Usage Guide



1\. \*\*Search by City\*\*: Enter any city name in the search box

2\. \*\*Click on Map\*\*: Click anywhere on the map to get weather for that location

3\. \*\*Time-Lapse\*\*: Drag the slider below Earth to visualize climate change (1980-2100)

4\. \*\*7-Day Forecast\*\*: Scroll down to see weekly forecast



\## 📊 DevOps Implementation



\### CI/CD Pipeline

```

Code Push → GitHub → CI Build → Docker Image → Deploy → Monitor

```



\### Infrastructure

\- \*\*Containerization\*\*: Docker \& Docker Compose

\- \*\*Orchestration\*\*: Kubernetes cluster (3 replicas)

\- \*\*Load Balancing\*\*: Kubernetes Service

\- \*\*Monitoring\*\*: Prometheus metrics + Grafana dashboards

\- \*\*Logging\*\*: ELK Stack / CloudWatch



\## 📁 Project Structure

```

weather-monitoring-devops/

├── index.html              # Main application file

├── Dockerfile              # Docker container configuration

├── docker-compose.yml      # Docker compose setup

├── Jenkinsfile            # Jenkins CI/CD pipeline

├── README.md              # Project documentation

├── .gitignore             # Git ignore rules

├── kubernetes/            # K8s manifests

│   ├── deployment.yaml

│   ├── service.yaml

│   └── ingress.yaml

├── assets/                # Static assets

└── docs/                  # Documentation

&nbsp;   └── screenshots/

```



\## 🔐 Environment Variables



Create a `.env` file (not included in repo):

```env

OPENWEATHER\_API\_KEY=your\_api\_key\_here

```



\## 🤝 Contributing



1\. Fork the repository

2\. Create feature branch (`git checkout -b feature/AmazingFeature`)

3\. Commit changes (`git commit -m 'Add AmazingFeature'`)

4\. Push to branch (`git push origin feature/AmazingFeature`)

5\. Open Pull Request



\## 📝 Git Workflow

```bash

\# Create feature branch

git checkout -b feature/new-feature



\# Make changes and commit

git add .

git commit -m "Description of changes"



\# Push to GitHub

git push origin feature/new-feature



\# Merge to main after review

git checkout main

git merge feature/new-feature

```



\## 🐳 Docker Commands

```bash

\# Build image

docker build -t weather-monitoring .



\# Run container

docker run -p 8080:80 weather-monitoring



\# Using docker-compose

docker-compose up -d

```



\## ☸️ Kubernetes Deployment

```bash

\# Apply configurations

kubectl apply -f kubernetes/



\# Check status

kubectl get pods

kubectl get services



\# Scale deployment

kubectl scale deployment weather-monitoring --replicas=5

```



\## 📈 Monitoring



\- \*\*Prometheus\*\*: http://localhost:9090

\- \*\*Grafana\*\*: http://localhost:3000

\- \*\*Application\*\*: http://localhost:8080



\## 🎓 Learning Outcomes



This project demonstrates:

\- ✅ Version control with Git/GitHub

\- ✅ Docker containerization

\- ✅ Kubernetes orchestration

\- ✅ CI/CD pipeline implementation

\- ✅ Cloud deployment strategies

\- ✅ Monitoring and logging setup

\- ✅ DevOps best practices



\## 📸 Screenshots



!\[Dashboard](docs/screenshots/dashboard.png)

!\[Interactive Map](docs/screenshots/map.png)

!\[Time-Lapse](docs/screenshots/timelapse.png)



\## 🐛 Known Issues



\- Weather API has rate limits (60 calls/minute for free tier)

\- Time-lapse slider visual effects are CSS-based (not real satellite data)



\## 🔜 Future Enhancements



\- \[ ] Add historical weather data charts

\- \[ ] Implement user authentication

\- \[ ] Add weather alerts and notifications

\- \[ ] Multi-language support

\- \[ ] Dark mode toggle

\- \[ ] PWA (Progressive Web App) support



\## 📞 Contact



\*\*Your Name\*\*

\- GitHub: \[@yourusername](https://github.com/yourusername)

\- Email: your.email@example.com

\- LinkedIn: \[Your LinkedIn](https://linkedin.com/in/yourprofile)



\## 📄 License



This project is licensed under the MIT License - see the LICENSE file for details.



\## 🙏 Acknowledgments



\- \[OpenWeatherMap](https://openweathermap.org/) - Weather data API

\- \[Leaflet.js](https://leafletjs.com/) - Interactive maps

\- DevOps community for inspiration and best practices



---



⭐ \*\*Star this repository if you find it helpful!\*\* ⭐



\*\*Made with ❤️ for DevOps Learning\*\*

