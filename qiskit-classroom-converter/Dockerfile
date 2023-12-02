FROM jupyter/minimal-notebook:python-3.11

LABEL maintainer="minwook shin <minwook0106@gmail.com>"

RUN pip install qiskit-classroom-converter==0.4.3
RUN wget https://raw.githubusercontent.com/KMU-quantum-classroom/qiskit-classroom-converter/main/qiskit_classroom_converter_public_demo.ipynb
RUN chmod +x ./qiskit_classroom_converter_public_demo.ipynb
