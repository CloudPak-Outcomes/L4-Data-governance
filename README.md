# L4-Data-governance
Data governance Level 4 course materials

## **PoX best practices** (4-6 hours)<br/>
### 1. **General PoX best practices** :white_check_mark:<br/>
- [General PoX best practices level 4 (YourLearning - 2 hours)](https://yourlearning.ibm.com/activity/PLAN-331A2AB52C0F)

### 2. **[Product-specific best practices](SpecificBestPractices.md)**<br/>
Product-specific framework for scoping and executing successful PoXs. Topics to include:
- Competitive considerations (/CI deck)
    - [Seismic: Data Science and MLOps and AI Governance Competitive (Apr 25, 2023)](https://ibm.seismic.com/Link/Content/DCmRVFDWFB4c28T24FXXDMpVH4pG)<br/>
    :scream: Includes 143 slides. Probably not what we want! :scream:<br>
- Environment deployment options for a PoX :interrobang:
> Similar to general one with specific of techzone, CPDaaS, install yourself (only if needed on client resources - hardware)<br/>
> Getting openscale to run on any env.<br/>
> --> Environment provisioning

- Resources to help plan and execute a PoX :interrobang:
> Talk to tech sales<br/>
> Nothing from Elena, maybe Carlo Appugliese
>
- Workshop guidance and materials
    - CPDaaS: Data fabric demos (repackage labs - pdf of md files?)
    - CPD: Analytics modernization workshop :interrobang:Where is it?:interrobang:
> Contact Dirk to find out where it is - and what needs to be done with it
- Product-specific lessons learned
> Nothing from Elena, maybe Carlo Appugliese
>
a. :rotating_light: Data science and MLOps best practices :rotating_light:

b. :rotating_light: AI governance best practices :rotating_light:

### 3. **Quiz**<br/>
TBD: To evaluate the preparedness for a technical PoX

## **[Product education, architecture, and sizing](ProductEducation/README.md)** (8-16 hours?)
### 1. **[Product deep technical education]((ProductEducation/README.md))**<br/>
- Installation
- Configuration
- Tuning
> Three items covered by Roger CPD stuff - :interrobang:Need clarification from Dirk:interrobang: 
- Connectivity with other products Troubleshooting
> What is it really? Amazon, Azure?
- Doc CPDaaS: Integrations with other cloud platforms (enough for connectivity?)
> Need some content to summarize integration
- What's new in 4.6: :white_check_mark:
    - [Seismic: What's new in Watson Studio on CPD 4.6 (Nov 30, 2022)](https://ibm.seismic.com/Link/Content/DCDbjc4bmpbg4GMTgdW7jGCffFM3)
    - [Seismic: CPD 4.6 What's new (Nov 30, 2022)](https://ibm.seismic.com/Link/Content/DC7m9dQgjjV7487Gg8DQXJ9cR9C8)
    - :books: [Doc: Feature differences between Cloud Pak for Data deployments](https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/feature-matrix.html?context=cpdaas&audience=wdp) :books:
- Misc technical stuff :white_check_mark:
    - [Data Science and MLOps client presentation level 2](https://ibm.seismic.com/Link/Content/DCqq9B366HXmq8F2TPVH4R2m8JM3)
    - [AI Governance client presentation level 2](https://ibm.seismic.com/Link/Content/DCVC27V9PcX8W8HGg8WdqHcMF4Hd)
    - [Data Science and ML with Data Fabric for Trustworthy AI.pptx](https://ibm.ent.box.com/s/oqdmnuan00ggveb2yqqlf4hrt7rdwe7o) :interrobang:

### **[2. Technical details and API access](ProductEducation/README.md#technical-details-and-api-access)**
- [CPD and CPDaaS technical details presentation (pptx)](https://github.com/CloudPak-Outcomes/L4-DSandMLOps-AIGovernance/blob/main/ProductEducation/UseAPI/powerpoint/TechnicalDetails.pptx) :white_check_mark:
- Architecture patterns
    - [expert labs architecture pattern pdf](https://ibm.seismic.com/Link/Content/DC9qM2QDPmQTX8WPRFmT4jh4DGGd) 
    - [AI Governance technology patterns](https://pages.github.ibm.com/skol/hypersonic-ai-governance/)
> See: https://ibm.ent.box.com/folder/199820890301 (Governance example)
>
- OpenScale and OpenPages
> Setting up openscales to talk to different providers
- CPD and CPDaaS automation management :construction:
    - [Using CPD and CPDaaS APIs](ProductEducation/UseAPI/README.md)
        - [User management](ProductEducation/UseAPI/01-UserManagement.md) :arrow_forward:
            - [CPD User management](ProductEducation/UseAPI/01a-UserMgmtCPD.md)
            - [CPDaaS User management](ProductEducation/UseAPI/01b-UserMgmtCPDaaS.md)
        - [Project management](ProductEducation/UseAPI/02-ProjectManagement.md) :arrow_forward:
        - [Services management](ProductEducation/UseAPI/03-ServicesManagement.md) :construction:
            - [Cloud Pak for Data (CPD)](ProductEducation/UseAPI/03-ServicesManagement.md#cloud-pak-for-data-cpd) :arrow_forward:
            - [Cloud Pak for Data as a Service](ProductEducation/UseAPI/03-ServicesManagement.md#cloud-pak-for-data-as-a-service-cpdaas) :construction:
        - [User reservation automation example](ProductEducation/UseAPI/04-ReservationExample.md) :construction:

### **[3. Sizing](ProductEducation/README.md#sizing)** :white_check_mark:
- Seismic: CPD 4.6 sizing (March 22, 2023)
- Seismic: Data Science and MLOps Pricing, Packaging, Sizing (Jan 18, 2023)
- Seismic: AI Governance Pricing, Packaging, Sizing (Apr 6, 2023)

### **4. Quizzes**
To test the product's technical knowledge after each main topic

## **[Instructions for essential hands-on tasks](HandsOnTasks/README.md)** (3-5 days?) :construction:

### **[1. Instructions for hands-on tasks](andsOnTasks/README.md)** 
- Training data generation :white_check_mark:
- General use cases :white_check_mark:
- Hands-on overall use case :arrow_forward:
- Data science and MLOps :construction:
    - Accessing/exploring insurance data :construction:
    - Accessing/exploring/cleansing public accident data
    - Accidents model creation
    - Risk factor model creation
    - Evaluation

- AI Governance
    - Deployment
    - Monitoring
    - More

### **2. Experiential test or scenario-based quiz**
To evaluate the learning

## **Additional resources**
- [Reference material](ReferenceMaterial.md)
- [Elena Lowery’s material](https://ibm.ent.box.com/s/he4rl1zx40k0zaeusscbzcd81fiel09z)
- [Byte-size data science](http://youtube.com/c/ByteSizeDataScience)
