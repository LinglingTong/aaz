# [Command] _databricks workspace vnet-peering update_

Update the vnet peering.

## Versions

### [2018-04-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kYXRhYnJpY2tzL3dvcmtzcGFjZXMve30vdmlydHVhbG5ldHdvcmtwZWVyaW5ncy97fQ==/2018-04-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.databricks/workspaces/{}/virtualnetworkpeerings/{} 2018-04-01 -->

#### examples

- Update the vnet peering (enable gateway transit and disable virtual network access).
    ```bash
        databricks workspace vnet-peering update --resource-group MyResourceGroup --workspace-name MyWorkspace -n MyPeering --allow-gateway-transit --allow-virtual-network-access false
    ```