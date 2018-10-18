# yoda-packages
Packaging for YoDa

Goal is to move the instructions subdir to the repo (and have it maintained there).

## Dependencies

On EL7, requires EPEL repos

    yum install -y GitPython ruby-devel gcc make rpm-build rubygems
    gem install --no-ri --no-rdoc fpm

## Run

Simple

    ./build.py
