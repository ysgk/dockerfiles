FROM circleci/node:12-browsers

# aws-cli をインストール
RUN apt-get install -y \
        python3-dev \
        python3-setuptools \
        python3-pip

RUN pip3 install awscli --upgrade --user

ENV PATH ~/.local/bin:$PATH

CMD ["node"]
