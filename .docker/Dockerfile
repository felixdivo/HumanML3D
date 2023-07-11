# syntax=docker/dockerfile:1

FROM continuumio/anaconda3:2019.03

# Mount the repository
#WORKDIR /app
#COPY . .
COPY environment-minimal.yaml environment-minimal.yaml

RUN conda env create -f environment-minimal.yaml
# RUN conda init sh
# RUN conda activate torch_render

#RUN cd body_model && \
#    tar --skip-old-files -xf dmpls.tar.xz && \
#    tar --skip-old-files -xf smplh.tar.xz

CMD ["bash"]
