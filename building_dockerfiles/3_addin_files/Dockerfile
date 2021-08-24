# start with previously created container
# or we could put the creation steps (minus CMD) here to start from scratch
FROM pkro/nanoer
# copy notes.txt in the current (context) directory into container
ADD notes.txt /notes.txt
CMD ["/bin/nano", "/notes.txt"]