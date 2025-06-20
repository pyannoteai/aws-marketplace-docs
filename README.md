# pyannoteAI AWS Marketplace Diarization model

This repository contains usage instructions for the [pyannoteAI AWS Marketplace Diarization Model](https://aws.amazon.com/marketplace/pp/prodview-mfmm2lfeq2q7u).

This solution provides precise diarization tools for businesses that require data security and accurate speaker labeling.

## Product Highlights

The Speaker Diarization Model enables accurate segmentation of audio recordings by detecting and labeling individual speakers across time. Designed for seamless integration into transcription pipelines, media workflows, and audio analytics systems, it supports a wide range of formats including WAV, MP3, FLAC, and OGG. The service is language-agnostic and works across diverse audio sourcecalls, meetings, interviews, podcasts, and more. With built-in support for mono and stereo channels, varying sample rates, and flexible input options it can be deployed in batch or near-real-time use cases. Key features include automatic speaker count estimation, precise time-stamped speaker labeling, and detection of overlapping speech. Outputs are returned in structured JSON for easy integration with transcription engines, search indexes, or business intelligence tools. Whether you are enriching speech-to-text transcripts, analyzing call center performance, or processing long-form media, this API improves clarity, organization, and data usability.

### Data Security

This solution operates within Amazon SageMaker, securely within your AWS account. Per AWS security policy, SageMaker deploys images in an environment devoid of network or AWS service endpoint access. This means that when you launch this product from AWS Marketplace, this model is deployed without network access. Additionally, AWS restricts the model from accessing the internet during runtime. Therefore, when you use this product, only you can access your data. For more detailed information about security and data access, please refer to the following resources [here](https://docs.aws.amazon.com/marketplace/latest/userguide/ml-security-and-intellectual-property.html) and [here](https://docs.aws.amazon.com/marketplace/latest/buyerguide/product-types-machine-learning-products.html).

Delivery method via SageMaker supports compliance certifications:
C5, CCCS, CISPE, DESC CSP, DoD CC SRG, ENS High, FedRAMP, FINMA, GSMA, HIPAA BAA, HITRUST CSF, IAR, IRAP, ISMAP, ISO and CSA STAR certificates, K-ISMS, MTCS, OSPAR, PCI, Pinakes, PiTuKri, SNI 27001, SOC. For further details, please visit this [page](https://aws.amazon.com/compliance/services-in-scope/).

### Features

#### Diarization (speaker detection and labeling)

This solution detects and labels any number of speakers. It can be used to segment audio recordings into speaker turns, providing precise time-stamped labels for each speaker. This is particularly useful for applications such as meeting transcription, call center analysis, and media content organization.

The number of speakers is automatically estimated, and the model can handle overlapping speech scenarios. The output is structured in JSON format, making it easy to integrate with transcription engines or other data processing systems.

#### Speaker Voiceprint

This mode creates a unique voiceprint for a single speaker, allowing for speaker identification across different audio files. It can be used to recognize speakers in new audio recordings based on their previously established voiceprint.

#### Speaker Identification

This mode identifies speakers in a given audio file by matching them against a set of known voiceprints. It can be used to determine who is speaking in a recording based on previously established voiceprints.

### Contact us

If you have any questions about our product, feel free to email us at support@pyannote.ai
