# WIP

### Why?

- Copa is essential to rapidly patch container images, ensuring security, reducing costs, and simplifying the patching process in a fast-paced operational environment.

### How?

![Copacetic](copacetic-how.png)

### Installation

1. Install Trivy

- ```wget https://github.com/aquasecurity/trivy/releases/download/v0.18.3/trivy_0.18.3_Linux-64bit.deb```

- ```sudo dpkg -i trivy_0.18.3_Linux-64bit.deb```

2. Install Copa CLI

- ```wget https://github.com/project-copacetic/copacetic/releases/download/v0.4.1/copa_0.4.1_linux_amd64.tar.gz```

- ```tar -xvf copa_0.4.1_linux_amd64.tar.gz```

- ```sudo mv copa /usr/local/bin```

### Test



### Resources
1. https://github.com/project-copacetic/copacetic
2. [Copacetic - Patch Your Container Images Seamlessly with COPA](https://www.youtube.com/watch?v=kDkBHV-V_3s)
3. https://github.com/aquasecurity/trivy