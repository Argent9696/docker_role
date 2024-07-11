# templates/Dockerfile.j2
FROM {{ base_image }}

RUN apt-get update && apt-get install -y {{ packages | join(' ') }}

CMD ["{{ command }}"]
