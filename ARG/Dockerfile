FROM almalinux:8
ARG username
RUN adduser $username
USER $username
ARG Place
ARG Country
RUN echo "place is ${Country}, City is ${Place}"
ENV place=${Place}
ENV Country=${Country}
CMD ["sleep","100"]