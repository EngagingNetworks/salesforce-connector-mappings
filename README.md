# salesforce-connector-mappings
## Understanding the Mapping Rule Engine
The Mapping Rule engine is the core of the transactional processing system, acting as a bridge between Engaging Networks Staging Records and your Salesforce objects. When supporter actions—such as donations, petition signatures, or email opens—are pushed from Engaging Networks to Salesforce daily, they arrive as raw staging records. The mapping rule engine then evaluates these records based on predefined lookup and directive rules to determine how that data should be written into specific Salesforce objects, such as Opportunities, Campaign Members, or custom objects.
## Importing and Exporting Mappings via JSON
Engaging Networks facilitates easy management and migration of these rules through JSON import and export functionality. This is particularly useful for creating backups or moving tested configurations from a Salesforce sandbox to a production environment.

### To Export a Mapping:
- Navigate to the Transaction Mapping area within your Engaging Networks dashboard.
- Select the mapping(s) you wish to save and use the Export option.
- The system will generate a JSON representation of the mapping rules, which can then be saved locally or committed to a repository.

### To Import a Mapping:
- In the same Transaction Mapping dashboard, select the Import option.
- Upload the desired JSON file containing your mapping configurations.
- Once imported, the rules will be available in your linked Salesforce org for final configuration and activation.
