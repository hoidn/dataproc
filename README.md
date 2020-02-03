# Basic data processing pipeline 
Robert Tang-Kong, 2020

Currently a major work in progress, don't expect anything magical yet
## Installation Instructions
Clone the repo

`$ git clone https://github.com/tangkong/dataproc.git`

 Install package
 
`$ pip install . `

## Basic structure
This package is split into operations and workflows, with significant inspiration taken from various workflow manages (Xi-cam, ...).  
- Operations are atomistic actions to be taken on data.
- Workflows connect these operations and check the validity of these connections