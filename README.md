<h1 align="center">Modular-Deployment-of-Microservices</h1>
<br/>
<table width="100%" align="center" style=" border-collapse: collapse;">
  <trstyle=" border-collapse: collapse;">
    <th style=" border-collapse: collapse;">
        <a href="https://www.consul.io/">
            <img src="https://cdn.freebiesupply.com/logos/large/2x/consul-3-logo-png-transparent.png" height="60px" width="90px" alt="Consul" />
        </a>
    </th> 
    <th>
        <a href="https://helm.sh/">
            <img src="https://helm.sh/img/helm.svg" height="60px" width="90px"  alt="Helm" />
        </a>
    </th>
    <th>
        <a href="https://kubernetes.io/">
            <img src="https://download.logo.wine/logo/Kubernetes/Kubernetes-Logo.wine.png" height="60px" width="90px" alt="Kubernetes" />
        </a>
    </th>
    <th>
        <a href="https://grafana.com/">
            <img src="https://seeklogo.com/images/G/grafana-logo-15BA0AFA8A-seeklogo.com.png" height="60px" width="90px"  alt="Grafana" />
        </a>
    </th>
    <th>
        <a href="https://prometheus.io/">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Prometheus_software_logo.svg/1200px-Prometheus_software_logo.svg.png" height="60px" width="90px"  alt="Prometheus" />
        </a>
    </th>
  </tr>
</table>
<ol>
  <li>Project Description
        <p>Hi 👋, This Project is about Modular Deployment of Micro-Services.We are going to Build, Deploy and Monitor a simple, multi-tier web application using Kubernetes, Consul, Prometheus, Grafana and Docker. This application consists of the following components:
        <ul>
        <li>A single-instance Redis master to store guestbook entries</li>
        <li>Multiple replicated Redis instances to serve reads</li>
        <li>Multiple web frontend instances</li>
        </ul>
        </p>  </li>
  <li>Tools and Technology
    <ul>
        <li><a href="https://helm.sh/">Helm</a></li>
        <li><a href="https://kubernetes.io/">Kubernetes</a></li>
        <li><a href="https://www.consul.io/">Consul</a></li>
        <li><a href="https://prometheus.io/">Prometheus</a></li>
        <li><a href="https://grafana.com/">Grafana</a></li>
    </ul>
  </li>
  <li>Modules
    <ul>
        <li><p>The project includes three modules for Modular Deployment of Microservices. The modules are Microservices Creation, Service Discovery, Monitoring.</p>
        <ul>
            <li><b>Microservice Creation</b>
                <ul><p>First module is about creation of microsevices. Basically we use two tier application which has backend and frontend. Counting microservices will work as a backend microservice and dashboard microservice will work as a frontend. The main application image will be pulled from dockerhub which is provided by hashicorp</p>
                <li><b>Input: </b><p>Write microservice configuration file, mostly to deploy any micorservice in kubernetes cluster we need two config file(.yaml) file one for deployment and other or services . we can do both in one(not recommended).</p></li>
                <li><b>Processing: </b><p>After writing all config(.yaml) file , create a helm chart.And install that helm chart. Helm will take care of everything for kubernetes pods, replica set as defined in config file.
                </p></li>
                <li><b>Output: </b><p>Wait for few sec let the pods up and running , go to browser type http://localhost:3000 , we will be able to see dashboard. 3000 is the port number which is already defined in config file.</p></li>
                </ul>
            </li>
            <li><b>Service Discovery</b>
                <ul><p>First module is about creation of microsevices. Basically we use two tier application which has backend and frontend. Counting microservices will work as a backend microservice and dashboard microservice will work as a frontend. The main application image will be pulled from dockerhub which is provided by hashicorp</p>
                <li><b>Input:</b></li>
                <li><b>Processing:</b></li>
                <li><b>Output:</b></li>
                </ul>
            </li>
            <li><b>Monitoring</b>
                <ul><p>First module is about creation of microsevices. Basically we use two tier application which has backend and frontend. Counting microservices will work as a backend microservice and dashboard microservice will work as a frontend. The main application image will be pulled from dockerhub which is provided by hashicorp</p>
                <li><b>Input:</b></li>
                <li><b>Processing:</b></li>
                <li><b>Output:</b></li>
                </ul>
            </li>
        </ul>
        </li>
    </ul>
  </li>
</ol> 


