Repository for playing with Docker and Semantic MediaWiki  [![Build Status](https://travis-ci.org/toniher/docker-SemanticMediaWiki.svg?branch=master)](https://travis-ci.org/toniher/docker-SemanticMediaWiki)

* Parameters are stored in vars.env file.
* A MariaDB and a NGINX based PHP images are created.
* bash smw-build.sh for building images and starting the process.
* bash smw-start.sh for starting processes once images are created.

Different branches provide different version combinations

Information is stored in vars.env (that can be modified and passed as argument to the scripts above)

* Configuration files such as: LocalSettings.local.php or LocalSettings.redis.php are kept as -v mounted files ($CONF_PATH location)

