# Overview

This document describes how access OCLC FAST authority to work with linked data. 

## OCLC FAST vocabulary

OCLC FAST (Faceted Application of Subject Terminology) is derived from the Library of Congress Subject Headings (LCSH), one of the library domain’s most widely-used subject terminology schemas.

[More Information](http://www.oclc.org/research/themes/data-science/fast.html)


# Usage

The configurations in `config/authorities/linked_data` directory are designed to work with [ld4l-labs/qa_server](https://github.com/ld4l-labs/qa_server) to provide normalized access and data results.  See the [ld4l-labs/linked_data_authorities documentation](https://github.com/ld4l-labs/linked_data_authorities/blob/master/README.md) for more information on setting up a qa_server.

## Supported Configurations

* oclcfast_direct.json - Provides a configuration for directly accessing the OCLC FAST vocabulary as provided by OCLC.
* oclcfast_ld4l_cache.json - Provides a configuration for accessing the LD4L-Labs cache of the OCLC FAST vocabulary.

[Technical Documentation](https://www.oclc.org/developer/develop/web-services/fast-api/linked-data.en.html)
[Download](http://www.oclc.org/research/themes/data-science/fast/download.html) (n-triples)