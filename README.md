[![Varbase](https://raw.githubusercontent.com/Vardot/varbase/11.0.x/images/varbase-logo.png)](https://www.drupal.org/project/varbase)

# Varbase Development Base

A recipe to manage default development modules and configurations.

## Description

Development Environment Modules, make sure to disable them in production.

This recipe provides essential development tools including:
- **dblog**: Database logging for debugging
- **views_ui**: Views user interface for content administration
- **config_update_ui**: Configuration update interface
- **devel**: Development tools and debugging utilities
- **sdc_devel**: Single Directory Components development tools
- **reroute_email**: Email rerouting for testing environments

## Installation

This is a Drupal recipe that can be applied using Drupal's recipe system.

## Configuration

The recipe includes default configurations for:
- Database logging settings
- Email rerouting to development catch-all
- Syslog settings for production-like logging

## Warning

**Important**: This recipe is intended for development environments only. Make sure to disable these features in production environments.

## Maintainers

- [Vardot](https://www.drupal.org/vardot)

## License

GPL-2.0-or-later
