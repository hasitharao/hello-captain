# hello-captain

Basic Dockerfile that prints "Hello, Captain!".

Project URL: printf '# hello-captain\n\nBasic Dockerfile that prints "Hello, Captain!".\n\nProject URL: %s\n\n## Usage\n\n    docker build -t hello-captain .\n    docker run --rm hello-captain\n' "$(pbpaste)" > README.md
cat README.md

## Usage

    docker build -t hello-captain .
    docker run --rm hello-captain
