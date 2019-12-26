## Build Postgres-XC RPM for EL 7.x

This project builds the Postgres-XL RPMs from 1.2.1 source file. 

I forked this project from `theory/postgres-xc-rpm`, and I have modified and tested the new project on CentOS 7.6 64-bit, it works file.

### How to use?

    git clone https://github.com/guobo507/postgres-xc-rpm.git
    cd postgres-xc-rpm/
    ./buildxc

### How to get the results?

When you finished, you can check the result by using the following command:

    cd ./RPMS/x86_64/
    ls -lh 

Or for source rpm package:

    cd ./RPMS/
    ls -lh 

