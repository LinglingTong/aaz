# [Command] _databricks workspace create_

Create a new workspace.

## Versions

### [2018-04-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kYXRhYnJpY2tzL3dvcmtzcGFjZXMve30=/2018-04-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.databricks/workspaces/{} 2018-04-01 -->

#### examples

- Create a workspace
    ```bash
        databricks workspace create --resource-group MyResourceGroup --name MyWorkspace --location westus --sku standard
    ```

- Create a workspace with managed identity for storage account
    ```bash
        az databricks workspace create --resource-group MyResourceGroup --name MyWorkspace --location eastus2euap --sku premium --prepare-encryption
    ```