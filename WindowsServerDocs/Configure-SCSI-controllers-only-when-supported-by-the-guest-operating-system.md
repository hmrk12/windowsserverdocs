---
title: Configure SCSI controllers only when supported by the guest operating system
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: 
  - hyper-v
  - techgroup-compute
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 861f194f-467e-4b07-a1c5-55b35f6327c4
---
# Configure SCSI controllers only when supported by the guest operating system
\[This information is preliminary and subject to change.\]

|||
|-|-|
|**Operating System**|[!INCLUDE[winthreshold_server_2](includes/winthreshold_server_2_md.md)]|
|**Product\/Feature**|Hyper\-V|
|**Severity**|Warning|
|**Category**|Configuration|

In the following sections, italics indicates UI text that appears in the Best Practices Analyzer tool for this issue.

## Issue

*A virtual machine is configured with a SCSI controller that cannot be used because the guest operating system does not support SCSI controllers.*

## Impact

*Virtual machines cannot use storage attached to the SCSI controller. This impacts the following virtual machines:*

\<list of virtual machines>

## Resolution

*Shut down the virtual machine and use Hyper\-V Manager to remove the SCSI controller from the virtual machine. Then, restart the virtual machine.*

