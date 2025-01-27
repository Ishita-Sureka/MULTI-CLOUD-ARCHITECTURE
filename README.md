# MULTI-CLOUD-ARCHITECTURE

# CLOUD-STORAGE-SETUP

**COMPANY**:CODTECH IT SOLUTIONS

**NAME**:ISHITA SUREKA

**INTERN ID**:CT08IXT

**DOMAIN**:CLOUD COMPUTING

**BATCH DURATION**: December 30th, 2024 to January 30th, 2025

**MENTOR NAME**: NEELA SANTOSH

**DESCRIPTION OF TASK**:This project involved designing and implementing a multi-cloud architecture where services were distributed across two major cloud platforms: Amazon Web Services (AWS) and Google Cloud Platform (GCP). The objective was to establish interoperability between these platforms by setting up a workflow where a file uploaded to an AWS S3 bucket would be accessible from GCP Cloud Storage. This task demonstrated the potential for seamless integration between two cloud providers, aligning with industry trends emphasizing multi-cloud strategies for enhanced flexibility and efficiency.

The process began with the setup of an AWS S3 bucket named aws-no-cost-storage-project, created under AWS’s free tier to ensure cost efficiency. The bucket served as the primary file storage location. Proper configurations were applied to secure the storage and control access. IAM policies were implemented to grant the required permissions for uploading and accessing files. The S3 bucket was tested by uploading sample files, ensuring functionality and validating access controls.

On the GCP side, a Cloud Storage bucket was created to serve as the destination for interoperability. Permissions on this bucket were configured to securely accept files originating from AWS. To facilitate the workflow between the two platforms, the GCP Storage Transfer Service was utilized. This service was configured to retrieve files from the S3 bucket using publicly accessible object URLs with appropriate permissions.

To achieve secure access, AWS S3’s pre-signed URLs feature was leveraged. Files uploaded to the S3 bucket were made temporarily accessible using these URLs, which were then manually input into the GCP Storage Transfer Service. This setup ensured that data could be securely retrieved and transferred without additional scripting.

Testing was a critical aspect of the project. A test file was uploaded to the S3 bucket, and its pre-signed URL was used in the Storage Transfer Service on GCP. The service successfully retrieved the file and stored it in the GCP bucket, demonstrating the effectiveness of the interoperability workflow. This process validated the functionality and security of the architecture, ensuring that the data transfer adhered to the intended requirements.

The deliverables for this project included a fully operational workflow demonstrating the transfer of files between AWS and GCP, as well as a comprehensive report documenting the setup and configurations. The report detailed the steps involved in creating and securing the S3 and GCP buckets, configuring access permissions, and enabling the transfer of files between platforms. These documents provide clear guidelines for replicating the workflow in similar scenarios.

In conclusion, this project successfully demonstrated a simple yet effective multi-cloud architecture. By utilizing AWS S3 and GCP Cloud Storage with minimal setup, the task showcased how organizations can leverage the strengths of multiple cloud platforms while maintaining security and functionality. The project’s simplicity and reliance on built-in cloud services make it an excellent starting point for understanding multi-cloud strategies and interoperability in real-world applications.

**OUTPUT OF TASK**:

