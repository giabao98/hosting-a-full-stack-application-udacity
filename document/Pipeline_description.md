### Pipeline Overview

1. **Code Commit and Pipeline Trigger**:
   - Developer commits code, initiating a new pipeline in CircleCI.
   
2. **Build Process**:
   - Set up environment: Node.js runtime, environment variables, and necessary packages for both frontend and backend.
   - Run linting to enforce coding standards.
   - Build both API and frontend repositories.

3. **Approval Step**:
   - Hold for user approval before deployment.

4. **Deployment to AWS**:
   - Configure environment variables, set up Node.js runtime on EC2, and deploy the application.

### Pipeline Flow

![Pipeline](/document/diagrams/pipeline.png)