wrote with chatgpt since im on a time crunch

# Roadmap



\## Milestone 0: Reproducible foundation



\- \[ ] Inventory the existing working ITR modding environment.

\- \[ ] Record the exact game build and executable fingerprint.

\- \[ ] Identify the Oculus UE4.27.1 source revision.

\- \[ ] Record required engine patches and their validation status.

\- \[ ] Identify the baseline UE4SS revision and ITR-specific changes.

\- \[ ] Document compiler, SDK, and Python requirements.

\- \[ ] Implement a read-only environment verification command.

\- \[ ] Reproduce the setup in a clean environment.



Exit criterion:

A second environment can reproduce the documented baseline.



\## Milestone 1: Complete example workflow



\- \[ ] Create a minimal custom map.

\- \[ ] Include an original material and material instance.

\- \[ ] Cook and package using the supported engine toolchain.

\- \[ ] Load the map through the runtime.

\- \[ ] Verify entry, interaction, and return to the hub.

\- \[ ] Verify repeated transitions and save/load behavior.

\- \[ ] Document the complete workflow.



Exit criterion:

The example works repeatedly from a fresh installation.



\## Later milestones



1\. Stable runtime and compatibility layer.

2\. Initial public API with working examples.

3\. Editor integration and content-authoring tools.

4\. Additional gameplay APIs.

5\. Packaging and dependency support.

6\. Stable public SDK release.



Later milestones will receive detailed requirements after the

foundation and example workflow have been validated.

