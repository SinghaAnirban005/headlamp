# Karpenter

This Headlamp plugin adds support for visualizing Karpenter's NodeClass custom resources in a user-friendly way.

✅ **Current Features**:

*   Displays a list of all available NodeClass resources in the cluster.
    
*   Shows key details such as constraints and provisioning metadata.


🚧 **Work in Progress**:This is an early version of the plugin. Future updates will include support for visualizing NodePools, real-time autoscaling decisions, and integration with Prometheus for provisioning metrics.

## Developing Headlamp plugins

For more information on developing Headlamp plugins, please refer to:

- [Getting Started](https://headlamp.dev/docs/latest/development/plugins/), How to create a new Headlamp plugin.
- [API Reference](https://headlamp.dev/docs/latest/development/api/), API documentation for what you can do
- [UI Component Storybook](https://headlamp.dev/docs/latest/development/frontend/#storybook), pre-existing components you can use when creating your plugin.
- [Plugin Examples](https://github.com/kubernetes-sigs/headlamp/tree/main/plugins/examples), Example plugins you can look at to see how it's done.
