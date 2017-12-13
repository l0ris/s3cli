Versions
Currently avaliable versions (by tag).

2.0.1 - s3cmd version 2.0.1

Usage

Credentials can be injected as volume by running:
docker run -it --rm --volume $HOME/.aws:/home/ec2-user/.aws loriss/s3cli s3cmd ls

To simplify things you can create an alias:
s3cli="docker run -it --rm --volume $HOME/.aws/ec2-user/.aws loriss/s3cli"
