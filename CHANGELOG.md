# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## Version v1.0.2 (2023-3-28)

- add backwards compatible syntax

## Version v1.0.1 (2022-12-14)

- refactor to tutor k8s do createuser

## Version v1.0.0 (2022-06-26)

General production release.

## Version v0.0.7 (2022-06-26)

Added ADMIN_EMAIL as an input parameter
run: tutor k8s createuser --password "$TUTOR_ADMIN_PASSWORD" --staff --superuser "$TUTOR_ADMIN_USER" "$TUTOR_ADMIN_EMAIL"

## Version v0.0.1 (2022-06-01)

**Experimental. Do not use in production.**

* Initial Git import
