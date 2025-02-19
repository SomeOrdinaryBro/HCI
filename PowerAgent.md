# Creating a Power Agent on Copilot Studio (2025 Update)

## 1. Accessing Copilot Studio
1. Go to [Copilot Studio](https://copilotstudio.microsoft.com/).
2. Log in or create a new account (free).
   - Provide your name, email, and phone number.
   - Complete the registration process.
3. Once logged in, you will be redirected to the Copilot Studio environment.

## 2. Creating a New Agent
1. Navigate to the **Create** section.
2. Click on **New Agent**.
   - There are multiple agent templates, but for customization, select **New Agent**.
3. Fill out the required details:
   - **Agent Name**: Provide a descriptive name.
   - **Icon**: Optional, but recommended for identification.
   - **Description**: Not required but can be added.
   - **Instructions**: Critical step – define the agent’s purpose and behavior.
     - Example: *You are a self-help agent that acts as a support assistant.*

## 3. Configuring Knowledge Sources
1. Initially, adding Word documents is not allowed until the agent is created.
2. If you have website links as knowledge sources, add them now.
3. Alternatively, knowledge sources can be added after the agent is created.

## 4. Creating the Agent
1. Click on **Create**.
2. Once the agent is created, proceed to **Knowledge**:
   - Scroll down and click **Add Knowledge**.
   - Add a **public website** as a knowledge source.
   - Upload relevant DPM documents.

## 5. Managing Knowledge Sources
- Ensure each client has a separate agent with only their specific DPM documents.
- Avoid mixing client-specific documents in one agent.
- **Finance and IT knowledge bases have been tested together successfully**.
- SharePoint can be used to set up knowledge sources, but it may require assistance from the administrator to create sites.

## 6. Creating Topics
### Understanding Topics
Topics are key to structuring the agent's knowledge and responses. Since this bot serves as a primary source of information, instead of manually searching through Word documents, users can ask the bot directly about processes and steps.

### Steps to Create Topics
1. Navigate to the **Topics** section in Copilot Studio.
2. Click on **Create New Topic**.
3. Name the topic based on the process or step it will cover.
4. Define **trigger phrases** – these are the questions or keywords users might ask. Example:
   - "How do I submit an IT request?"
   - "What is the process for employee onboarding?"
5. In the response section, configure answers based on existing documentation.
   - Use text responses to provide clear, step-by-step instructions.
   - Link to additional resources if needed.
   - Configure follow-up questions to guide users through multi-step processes.
6. Test the topic to ensure it responds accurately to user queries.
7. Save and organize topics into categories for better structuring.

## 7. Testing the Agent
1. Use the **Test** feature within Copilot Studio to verify responses.
2. Check if the knowledge sources are being utilized correctly.
3. Adjust settings or add missing knowledge sources if necessary.

## 8. Publishing the Agent
1. Click on **Publish** to make the agent live.
2. Ensure all necessary configurations are in place before publishing.

## 9. Adding the Agent to Microsoft Teams
1. Navigate to **Channels**.
2. Select **Microsoft Teams**.
3. Follow the on-screen instructions to integrate the agent.
4. Deploy the agent to relevant Teams channels for user access.
