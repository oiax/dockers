FROM vvakame/review:2.3

RUN apt-get install -y --no-install-recommends texlive-fonts-extra

RUN gem install specific_install
RUN gem specific_install -l "git://github.com/kuroda/review.git" -b makeindex
