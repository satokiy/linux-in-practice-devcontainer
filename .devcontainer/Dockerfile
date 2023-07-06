FROM ubuntu:20.04
RUN ln -sf /usr/share/zoneinfo/Asia/Tokyo /etc/localtime
RUN apt update && apt install sudo -y
RUN sudo apt install -y binutils build-essential golang sysstat python3-matplotlib python3-pil fonts-takao fio qemu-kvm virt-manager libvirt-clients virtinst jq docker.io containerd libvirt-daemon-system
RUN sudo adduser `id -un` libvirt
RUN sudo adduser `id -un` libvirt-qemu
RUN sudo adduser `id -un` kvm