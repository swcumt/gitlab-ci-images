FROM tomkukral/buildah
RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
RUN dnf install -y zip
RUN unzip awscliv2.zip
RUN ./aws/install