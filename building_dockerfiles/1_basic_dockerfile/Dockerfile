# Specify what image to start from. busybox is supertiny with a shell
FROM busybox
# In that container, echo something
RUN echo "building simple docker image"
# set command to run when the image is started
# there can be only one CMD in a dockerfile;
# if there are multiple, only the last one will take effect
CMD echo "Hello container"