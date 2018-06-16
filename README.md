# nv-dkr
tiny script that helps running nvidia dockers similar to vagrant

## Prerequisites

- docker-ce
- [nvidia-docker](https://github.com/NVIDIA/nvidia-docker)

[Install nvidia-docker on zesty](http://blog.carbocation.com/post/160049289407/installing-nvidia-docker-on-ubuntu-1704-zesty)

## Install

    $ pip install git+https://github.com/rk4n/nv-dkr --user

## Usage

    $ dkr i nvidia/cuda:9.2-cudnn7-devel-ubuntu16.04 --nvidia
    $ dkr up

    $ dkr destroy

Examples:
- `nvidia/cuda`
- `tensorflow/tensorflow:latest-gpu`
- `pytorch/pytorch`
- `continuumio/miniconda`
