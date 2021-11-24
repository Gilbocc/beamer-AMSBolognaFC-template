FROM qmcgaw/latexdevcontainer:latest
USER root
RUN apt-get update --allow-releaseinfo-change && apt-get -y install python
RUN tlmgr update --self
RUN tlmgr install texliveonfly elsarticle wasy
