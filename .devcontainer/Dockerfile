FROM php


# Avoid warnings by switching to noninteractive
ENV DEBIAN_FRONTEND=noninteractive

RUN  

RUN  echo "alias artisan='php artisan'" >> /root/.bashrc && \
     echo "alias serve='php artisan serve --port=8000 --host=0.0.0.0'" >> /root/.bashrc && \
     echo "alias ls='ls -B -h --color=auto -ltr'" >> /root/.bashrc && \
    #  echo "alias _='sudo'" >> /root/.bashrc  && \
     echo "alias apt='sudo apt'" >> /root/.bashrc  && \
     echo "alias apt-get='sudo apt-get'" >> /root/.bashrc

# Switch back to dialog for any ad-hoc use of apt-get
ENV DEBIAN_FRONTEND=