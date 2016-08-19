# Supported tags and `Dockerfile` links

- [`latest` (*Dockerfile*)](https://github.com/craigvincent/docker-nunit-console/Dockerfile)
- [`3.4.1` (*Dockerfile*)](https://github.com/craigvincent/docker-nunit-console/tree/3.4.1/Dockerfile)
- [`2.6.4` (*Dockerfile*)](https://github.com/craigvincent/docker-nunit-console/tree/2.6.4/Dockerfile)

# What is nunit-console

nunit-console is part of the [NUnit unit-testing framework](http://www.nunit.org/), it allows you to run your unit tests from the command line as seen [here](http://www.nunit.org/index.php?p=nunit-console&r=2.6.4).

# How to use this image
This image features an entrypoint for nunit-console. Attach a volume containing assemblies and set it as the working directory.

    docker run -v "/path/to/assemblies:/test" --workdir /test craigvincent/docker-nunit-console [nunit console arguments]

# Issues

Please report issues on the [GitHub project](https://github.com/craigvincent/docker-nunit-console).
