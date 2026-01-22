# IDN CP to RO Create

Software that converts IDN CP metadata to/from RO Crates metadata.

#### Modules

* **Converter**
    * converts [IDN CP metadata](https://data.idnau.org/pid/cp/spec) to and from RO Crates metadata
    * _in progress_
* **Spreadsheet Processor**
    * converts MS Excel and CSV data to IDN CP and/or RO Crates metadata
    * _in progress_

## Use

#### validation

Within Python, use `validate.py`, the package [roc-validator](https://pypi.org/project/roc-validator/) is called. 

The command line equivalent is:

```
uv run rocrate-validator validate tests/data/crate-valid-01 {PATH-TO-CRATE}
```



## Licensing & Rights

The creators and maintainers of this software wish for it to be available for use as widely as possible. The software is thus licensed using the very permissive https://opensource.org/licenses/BSD-3-Clause[BSD 3-Clause] software license, a copy of the deed of which is in the file LICENSE.

This software is copyright as follows:

(c) Indigenous Data Network, 2026


## Contact

#### For development:

**Nicholas Car**  
_Data Architect_  
[KurrawongAI](https://kurrawong.ai)  
<nick@kurrawong.ai>  

#### For ongoing tool management:

**Jamie Feiss** +
_Data Infrastructure Developer_  
[Indigenous Studies Unit](https://mspgh.unimelb.edu.au/centres-institutes/onemda/research-group/indigenous-studies-unit)  
University of Melbourne  
<jamie.feiss@unimelb.edu.au>