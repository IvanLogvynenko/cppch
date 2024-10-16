FROM fedora:40

RUN dnf install -y clang llvm clang-tools-extra cmake git gtest-devel libasan libubsan python3-lit diffutils && dnf clean all
ENV CXX=/usr/bin/clang++-18
ENV CC=/usr/bin/clang-18

WORKDIR /homework

COPY * ./

CMD [ "./eval.sh"]