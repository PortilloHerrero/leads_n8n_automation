# Customer Messaging Workflow

## Overview

Welcome to the **Customer Messaging Workflow** repository. This project is designed to automate and personalize customer communications using the n8n workflow automation tool. 
By integrating with various data sources and leveraging automation, this workflow ensures that each customer receives tailored, relevant messages, enhancing engagement and optimizing communication strategies.

## Key Features

- **Data Collection**: Gathers customer information and interaction history from Google Sheets.
- **Message Customization**: Merges customer data with predefined message templates.
- **Personalization**: Applies dynamic data to personalize messages for each customer.
- **Automated Delivery**: Sends personalized messages through automated channels.
- **Logging and Analysis**: Records sent messages and allows for performance analysis.

## Workflow Components

1. **Scheduled Trigger**: Automatically initiates the workflow at predefined intervals.
2. **Google Sheets Integration**: Two key sheets, one for customer data (Leads) and one for message templates (Messages), serve as the backbone of the workflow.
3. **Data Merging**: Combines customer data with the appropriate message template to create personalized messages.
4. **Message Personalization**: Dynamically inserts customer-specific details into each message.
5. **Batch Processing**: Handles large volumes of messages efficiently, ensuring orderly delivery.
6. **Send Condition**: Evaluates specific conditions before sending messages to ensure relevance.
7. **Delivery Logging**: Logs every sent message in Google Sheets for tracking and analysis.
8. **Telegram Notification**: Sends real-time notifications to the team upon successful message delivery.

## Benefits

- **Efficiency**: Automates repetitive tasks, allowing for significant time and resource savings.
- **Cost Savings**: Reduces manual labor costs associated with customer communication.
- **Scalability**: Handles large volumes of communications without a proportional increase in costs.
- **Improved Engagement**: Personalizes every interaction, enhancing customer loyalty and satisfaction.

## Installation

To use this workflow in your own n8n instance, follow these steps:

1. **Download the JSON File**: 
   - Download the `Customer_Messaging_Workflow.json` file from this repository.

2. **Import into n8n**:
   - Go to your n8n instance.
   - Click on the "Import" button in the top right corner of the dashboard.
   - Select the `Customer_Messaging_Workflow.json` file you downloaded.
   - Click "Import" to add the workflow to your n8n.

3. **Configure Credentials**:
   - Set up the necessary credentials (e.g., Google Sheets, Telegram) in your n8n instance to ensure the workflow operates correctly.

4. **Prepare Google Sheets**:
   - Ensure you have set up the required Google Sheets:
     - **Leads Sheet**: A sheet containing customer data such as names, email addresses, and interaction history.
     - **Messages Sheet**: A sheet containing message templates categorized by customer interaction levels.
   - Make sure the structure of your Google Sheets matches the structure expected by the workflow.

5. **Run the Workflow**:
   - You can now run the workflow manually to test it or activate it to run automatically based on the defined trigger.

## Usage

This workflow is designed to run automatically at scheduled intervals, sending personalized messages to customers based on their interaction history. It includes safeguards to ensure messages are only sent when appropriate and logs all activities for future analysis.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your improvements. Whether it's bug fixes, new features, or improvements to the documentation, your help is appreciated.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For any questions or feedback, please contact me (Pablo Portillo) at portilloherreropablo.pph@gmail.com or pablo_portill7@hotmail.com
