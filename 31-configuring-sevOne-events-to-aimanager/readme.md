# Configure SevOne to forward events to the WAIOps Probe for SevOne

This document explains about how to Configure IBM **SevOne** to forward events to the WAIOps Probe for SevOne

## 1. Install SevOne Probe

Install SevOne Probe in any of the Openshift cluster. You can use the same Openshift cluster where WAIOps is installed.

Here are the steps and script to install the Probe. [../21-install-sevone-probe-aimgr](../21-install-sevone-probe-aimgr)

## 2. Create WebHook in SevOne

Create Webhook in SevOne to forward live events to WAIOps SevOne Probe that we created in the above step.

Refer [../22-sevone-webhook-creation](../22-sevone-webhook-creation)

## 3. Configuring SevOne events-to-aimanager

Create SevOne Policies to forward live events to SevOne Probe.

Refer [../23-sevone-policy-creation](../23-sevone-policy-creation)

