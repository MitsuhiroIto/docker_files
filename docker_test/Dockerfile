FROM valian/docker-python-opencv-ffmpeg:py3

RUN pip install numpy
RUN apt-get install -y git
RUN git clone https://github.com/MitsuhiroIto/shell_script.git
RUN sh shell_script/batch_test/fetch_and_run.sh
