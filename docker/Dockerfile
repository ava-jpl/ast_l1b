FROM hysds/pge-base:latest
MAINTAINER jlinick "Justin.P.Linick@jpl.nasa.gov"
LABEL description="Ingest products from metadata"

USER ops

COPY . /home/ops/verdi/ops/ast_l1b

WORKDIR /home/ops
CMD ["/bin/bash", "--login"]

