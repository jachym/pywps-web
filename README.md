HOWTO manage PyWPS Homepage
===========================

step #1: edit source/*


step #2: run

    make html


step #3: rsync

    rsync --protocol 29  -r build/html/ $DEVELOPER@wald.intevation.org:/pywps/htdocs/ # --delete-excluded --del
