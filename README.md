# Exploring Crossplane project with Linode : A Weekend Project

This weekend, I dove into the world of Kubernetes and cloud resource management with a tool that's been gaining traction among DevOps enthusiasts: Crossplane. Using Linode, I embarked on a journey to streamline my cloud infrastructure, and here's a glimpse into that adventure.

Crossplane stands out in the cloud-native landscape for its unique approach to managing cloud resources. It operates on a declarative model, constantly checking and applying the desired state to your infrastructure, preventing the dreaded configuration drift that often plagues Terraform users.

Here's how I spent my weekend with Crossplane and Linode:

1. Kickstarted the project by enabling Kubernetes through Docker Desktop.
2. Installed Helm on Windows Subsystem for Linux (WSL) to manage Kubernetes applications.
3. Deployed Crossplane using Helm, setting the stage for the magic to happen.
4. Crafted a `provider.yaml` for Linode, integrating my cloud provider seamlessly with Kubernetes.
5. Created a `deployment.yaml` to spin up a Linode instance, all managed within the Kubernetes ecosystem.
6. Explored ways to tidy up, ensuring clean and efficient resource management.

The experience was not just about learning a new tool; it was about embracing a new philosophy in cloud computing. Crossplane with Linode proved to be a powerful duo, offering a glimpse into the future of infrastructure as code.

For those looking to explore this combo, the weekend is a perfect time to start. It's a journey worth taking for any cloud enthusiast or Kubernetes aficionado. Dive in, and let Crossplane and Linode guide you to a more organized, efficient, and scalable cloud experience. Happy exploring!

## Reference Links
- https://www.linode.com/docs/guides/getting-started-with-crossplane/
- https://marketplace.upbound.io/providers/linode/provider-linode/v0.0.19
