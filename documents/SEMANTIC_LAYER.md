<br /><br />
<p align="center">
    <img alt="PODAF Logo" src="https://github.com/charlyspoton/podaf/blob/main/branding/podaf-logo.png?raw=true" width="40%">
</p>


# PODA Ontology: semantic layer

It's crazy, but one of the biggest problems in the world of data is that we talk about the same thing with different names, in different ways, and from different perspectives. Aligning different stakeholders using a common language already solves a large part of the problem that PODAF is trying to address. So, here we go!

Below, we define the necessary elements for talking about data. Everything has its underlying technology; we know there are pipelines, databases, technologies, and so on. But let's try to understand the pieces without thinking about the technology. 

> To our techie friends, continuing to read this could help you solve problems for ordinary people, but if talking about data without thinking about technology makes you nervous, we recommend checking out the work done by LF AI & Data Foundation with Open Lineage.

## Data objects: pieces of information
Type: `data_object`

Data objects are the core element of ontology, which is why we're here. 

> We consider a data object to be any element that contains information that provides value to the user and also represents an element or elements of the real world.

We don't mean that the element has to exist in the physical, tangible world, but we do want to distinguish between data that represents something from the real world or the business and data that provides context about the data, known as metadata.


## Metadata objects: pieces of context
**Type:** `metadata_object`

## Data jobs: actions 
**Type:** `data_job`

Data jobs encompass the actions performed on data objects. In other words, they are actions that are carried out on data objects or that have an effect on data objects within our system.

### Capture: bringing data to the system
**Type:** `capture`
- **Input:** Nothing, since the element is outside our system
- **Output:** A data object, within our system, ready to be manipulated by the data agents.

This job is normally...

### Transform: crafting data objects
**Type:** `transform`

### Quality test: validating quality of data objects
**Type:** `quality_test`


## Data Agent: the doers
**Type:** `data_agent`

### Ingestor agent

### Transformer agent

### Validator agent

### Duplicator agent

### Uploader agent


## Data Experience: the why
**Type:** `data_experience`

### Visual experience

### Analytical experience

## Data User: the who
**Type:** `data_user`
