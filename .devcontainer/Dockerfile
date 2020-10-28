FROM linuxbrew/brew

RUN brew install futhark
RUN apt update && apt install -y python3-pip

RUN pip3 install -r requirements.txt

# ** [Optional] Uncomment this section to install additional packages. **
# RUN apk update \
#     && apk add --no-cache <your-package-list-here>
