# About

Microsoft Azure Online Storage is a component of the Nuxeo platform that offers the option of storing files - the attachments that are uploaded within a content object, Nuxeo binaries - in a Microsoft Azure container.

# Building

    mvn clean install

# Testing

To run the tests, use '-Pitest' (or run from ftest/webdriver).

This requires:

- having your Azure name and secret key in your environment (used by the binary manager)
- having azure cmd installed and configured with the same keys (used for cleanup)

# Configuration

See [nuxeo-core-binarymanager-azure README](https://github.com/nuxeo/nuxeo-core-binarymanager-cloud/tree/master/nuxeo-core-binarymanager-azure) for more informations.

# Resources

## Documentation

*TODO*

## Reporting issues

https://jira.nuxeo.com/browse/NXP/

# Licensing

[GNU Lesser General Public License (LGPL) v2.1](http://www.gnu.org/licenses/lgpl-2.1.html)

# About Nuxeo

Nuxeo dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with
SaaS-based tools and a modular architecture, the Nuxeo Platform and Products provide clear business value to some of the most recognizable brands including Verizon, Electronic Arts, Sharp, FICO, the U.S. Navy, and Boeing. Nuxeo is headquartered in New York and Paris.
More information is available at [www.nuxeo.com](http://www.nuxeo.com).
