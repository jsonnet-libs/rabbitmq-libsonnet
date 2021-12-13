---
permalink: /1.7/rabbitmq/v1beta1/rabbitmqCluster/
---

# rabbitmq.v1beta1.rabbitmqCluster

"RabbitmqCluster is the Schema for the RabbitmqCluster API. Each instance of this object corresponds to a single RabbitMQ cluster."

## Index

* [`fn new(name)`](#fn-new)
* [`obj metadata`](#obj-metadata)
  * [`fn withAnnotations(annotations)`](#fn-metadatawithannotations)
  * [`fn withAnnotationsMixin(annotations)`](#fn-metadatawithannotationsmixin)
  * [`fn withClusterName(clusterName)`](#fn-metadatawithclustername)
  * [`fn withCreationTimestamp(creationTimestamp)`](#fn-metadatawithcreationtimestamp)
  * [`fn withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)`](#fn-metadatawithdeletiongraceperiodseconds)
  * [`fn withDeletionTimestamp(deletionTimestamp)`](#fn-metadatawithdeletiontimestamp)
  * [`fn withFinalizers(finalizers)`](#fn-metadatawithfinalizers)
  * [`fn withFinalizersMixin(finalizers)`](#fn-metadatawithfinalizersmixin)
  * [`fn withGenerateName(generateName)`](#fn-metadatawithgeneratename)
  * [`fn withGeneration(generation)`](#fn-metadatawithgeneration)
  * [`fn withLabels(labels)`](#fn-metadatawithlabels)
  * [`fn withLabelsMixin(labels)`](#fn-metadatawithlabelsmixin)
  * [`fn withManagedFields(managedFields)`](#fn-metadatawithmanagedfields)
  * [`fn withManagedFieldsMixin(managedFields)`](#fn-metadatawithmanagedfieldsmixin)
  * [`fn withName(name)`](#fn-metadatawithname)
  * [`fn withNamespace(namespace)`](#fn-metadatawithnamespace)
  * [`fn withOwnerReferences(ownerReferences)`](#fn-metadatawithownerreferences)
  * [`fn withOwnerReferencesMixin(ownerReferences)`](#fn-metadatawithownerreferencesmixin)
  * [`fn withResourceVersion(resourceVersion)`](#fn-metadatawithresourceversion)
  * [`fn withSelfLink(selfLink)`](#fn-metadatawithselflink)
  * [`fn withUid(uid)`](#fn-metadatawithuid)
* [`obj spec`](#obj-spec)
  * [`fn withImage(image)`](#fn-specwithimage)
  * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-specwithimagepullsecrets)
  * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-specwithimagepullsecretsmixin)
  * [`fn withReplicas(replicas)`](#fn-specwithreplicas)
  * [`fn withSkipPostDeploySteps(skipPostDeploySteps)`](#fn-specwithskippostdeploysteps)
  * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specwithterminationgraceperiodseconds)
  * [`fn withTolerations(tolerations)`](#fn-specwithtolerations)
  * [`fn withTolerationsMixin(tolerations)`](#fn-specwithtolerationsmixin)
  * [`obj spec.affinity`](#obj-specaffinity)
    * [`obj spec.affinity.nodeAffinity`](#obj-specaffinitynodeaffinity)
      * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
      * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
      * [`obj spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
        * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
        * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
    * [`obj spec.affinity.podAffinity`](#obj-specaffinitypodaffinity)
      * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
      * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
      * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
      * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
    * [`obj spec.affinity.podAntiAffinity`](#obj-specaffinitypodantiaffinity)
      * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
      * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
      * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
      * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
  * [`obj spec.override`](#obj-specoverride)
    * [`obj spec.override.service`](#obj-specoverrideservice)
      * [`obj spec.override.service.metadata`](#obj-specoverrideservicemetadata)
        * [`fn withAnnotations(annotations)`](#fn-specoverrideservicemetadatawithannotations)
        * [`fn withAnnotationsMixin(annotations)`](#fn-specoverrideservicemetadatawithannotationsmixin)
        * [`fn withLabels(labels)`](#fn-specoverrideservicemetadatawithlabels)
        * [`fn withLabelsMixin(labels)`](#fn-specoverrideservicemetadatawithlabelsmixin)
      * [`obj spec.override.service.spec`](#obj-specoverrideservicespec)
        * [`fn withAllocateLoadBalancerNodePorts(allocateLoadBalancerNodePorts)`](#fn-specoverrideservicespecwithallocateloadbalancernodeports)
        * [`fn withClusterIP(clusterIP)`](#fn-specoverrideservicespecwithclusterip)
        * [`fn withClusterIPs(clusterIPs)`](#fn-specoverrideservicespecwithclusterips)
        * [`fn withClusterIPsMixin(clusterIPs)`](#fn-specoverrideservicespecwithclusteripsmixin)
        * [`fn withExternalIPs(externalIPs)`](#fn-specoverrideservicespecwithexternalips)
        * [`fn withExternalIPsMixin(externalIPs)`](#fn-specoverrideservicespecwithexternalipsmixin)
        * [`fn withExternalName(externalName)`](#fn-specoverrideservicespecwithexternalname)
        * [`fn withExternalTrafficPolicy(externalTrafficPolicy)`](#fn-specoverrideservicespecwithexternaltrafficpolicy)
        * [`fn withHealthCheckNodePort(healthCheckNodePort)`](#fn-specoverrideservicespecwithhealthchecknodeport)
        * [`fn withIpFamilies(ipFamilies)`](#fn-specoverrideservicespecwithipfamilies)
        * [`fn withIpFamiliesMixin(ipFamilies)`](#fn-specoverrideservicespecwithipfamiliesmixin)
        * [`fn withIpFamilyPolicy(ipFamilyPolicy)`](#fn-specoverrideservicespecwithipfamilypolicy)
        * [`fn withLoadBalancerIP(loadBalancerIP)`](#fn-specoverrideservicespecwithloadbalancerip)
        * [`fn withLoadBalancerSourceRanges(loadBalancerSourceRanges)`](#fn-specoverrideservicespecwithloadbalancersourceranges)
        * [`fn withLoadBalancerSourceRangesMixin(loadBalancerSourceRanges)`](#fn-specoverrideservicespecwithloadbalancersourcerangesmixin)
        * [`fn withPorts(ports)`](#fn-specoverrideservicespecwithports)
        * [`fn withPortsMixin(ports)`](#fn-specoverrideservicespecwithportsmixin)
        * [`fn withPublishNotReadyAddresses(publishNotReadyAddresses)`](#fn-specoverrideservicespecwithpublishnotreadyaddresses)
        * [`fn withSelector(selector)`](#fn-specoverrideservicespecwithselector)
        * [`fn withSelectorMixin(selector)`](#fn-specoverrideservicespecwithselectormixin)
        * [`fn withSessionAffinity(sessionAffinity)`](#fn-specoverrideservicespecwithsessionaffinity)
        * [`fn withTopologyKeys(topologyKeys)`](#fn-specoverrideservicespecwithtopologykeys)
        * [`fn withTopologyKeysMixin(topologyKeys)`](#fn-specoverrideservicespecwithtopologykeysmixin)
        * [`fn withType(type)`](#fn-specoverrideservicespecwithtype)
        * [`obj spec.override.service.spec.sessionAffinityConfig`](#obj-specoverrideservicespecsessionaffinityconfig)
          * [`obj spec.override.service.spec.sessionAffinityConfig.clientIP`](#obj-specoverrideservicespecsessionaffinityconfigclientip)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specoverrideservicespecsessionaffinityconfigclientipwithtimeoutseconds)
    * [`obj spec.override.statefulSet`](#obj-specoverridestatefulset)
      * [`obj spec.override.statefulSet.metadata`](#obj-specoverridestatefulsetmetadata)
        * [`fn withAnnotations(annotations)`](#fn-specoverridestatefulsetmetadatawithannotations)
        * [`fn withAnnotationsMixin(annotations)`](#fn-specoverridestatefulsetmetadatawithannotationsmixin)
        * [`fn withLabels(labels)`](#fn-specoverridestatefulsetmetadatawithlabels)
        * [`fn withLabelsMixin(labels)`](#fn-specoverridestatefulsetmetadatawithlabelsmixin)
      * [`obj spec.override.statefulSet.spec`](#obj-specoverridestatefulsetspec)
        * [`fn withPodManagementPolicy(podManagementPolicy)`](#fn-specoverridestatefulsetspecwithpodmanagementpolicy)
        * [`fn withReplicas(replicas)`](#fn-specoverridestatefulsetspecwithreplicas)
        * [`fn withServiceName(serviceName)`](#fn-specoverridestatefulsetspecwithservicename)
        * [`fn withVolumeClaimTemplates(volumeClaimTemplates)`](#fn-specoverridestatefulsetspecwithvolumeclaimtemplates)
        * [`fn withVolumeClaimTemplatesMixin(volumeClaimTemplates)`](#fn-specoverridestatefulsetspecwithvolumeclaimtemplatesmixin)
        * [`obj spec.override.statefulSet.spec.selector`](#obj-specoverridestatefulsetspecselector)
          * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspecselectorwithmatchexpressions)
          * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspecselectorwithmatchexpressionsmixin)
          * [`fn withMatchLabels(matchLabels)`](#fn-specoverridestatefulsetspecselectorwithmatchlabels)
          * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specoverridestatefulsetspecselectorwithmatchlabelsmixin)
        * [`obj spec.override.statefulSet.spec.template`](#obj-specoverridestatefulsetspectemplate)
          * [`obj spec.override.statefulSet.spec.template.metadata`](#obj-specoverridestatefulsetspectemplatemetadata)
            * [`fn withAnnotations(annotations)`](#fn-specoverridestatefulsetspectemplatemetadatawithannotations)
            * [`fn withAnnotationsMixin(annotations)`](#fn-specoverridestatefulsetspectemplatemetadatawithannotationsmixin)
            * [`fn withLabels(labels)`](#fn-specoverridestatefulsetspectemplatemetadatawithlabels)
            * [`fn withLabelsMixin(labels)`](#fn-specoverridestatefulsetspectemplatemetadatawithlabelsmixin)
            * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatemetadatawithname)
            * [`fn withNamespace(namespace)`](#fn-specoverridestatefulsetspectemplatemetadatawithnamespace)
          * [`obj spec.override.statefulSet.spec.template.spec`](#obj-specoverridestatefulsetspectemplatespec)
            * [`fn withActiveDeadlineSeconds(activeDeadlineSeconds)`](#fn-specoverridestatefulsetspectemplatespecwithactivedeadlineseconds)
            * [`fn withAutomountServiceAccountToken(automountServiceAccountToken)`](#fn-specoverridestatefulsetspectemplatespecwithautomountserviceaccounttoken)
            * [`fn withContainers(containers)`](#fn-specoverridestatefulsetspectemplatespecwithcontainers)
            * [`fn withContainersMixin(containers)`](#fn-specoverridestatefulsetspectemplatespecwithcontainersmixin)
            * [`fn withDnsPolicy(dnsPolicy)`](#fn-specoverridestatefulsetspectemplatespecwithdnspolicy)
            * [`fn withEnableServiceLinks(enableServiceLinks)`](#fn-specoverridestatefulsetspectemplatespecwithenableservicelinks)
            * [`fn withEphemeralContainers(ephemeralContainers)`](#fn-specoverridestatefulsetspectemplatespecwithephemeralcontainers)
            * [`fn withEphemeralContainersMixin(ephemeralContainers)`](#fn-specoverridestatefulsetspectemplatespecwithephemeralcontainersmixin)
            * [`fn withHostAliases(hostAliases)`](#fn-specoverridestatefulsetspectemplatespecwithhostaliases)
            * [`fn withHostAliasesMixin(hostAliases)`](#fn-specoverridestatefulsetspectemplatespecwithhostaliasesmixin)
            * [`fn withHostIPC(hostIPC)`](#fn-specoverridestatefulsetspectemplatespecwithhostipc)
            * [`fn withHostNetwork(hostNetwork)`](#fn-specoverridestatefulsetspectemplatespecwithhostnetwork)
            * [`fn withHostPID(hostPID)`](#fn-specoverridestatefulsetspectemplatespecwithhostpid)
            * [`fn withHostname(hostname)`](#fn-specoverridestatefulsetspectemplatespecwithhostname)
            * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-specoverridestatefulsetspectemplatespecwithimagepullsecrets)
            * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-specoverridestatefulsetspectemplatespecwithimagepullsecretsmixin)
            * [`fn withInitContainers(initContainers)`](#fn-specoverridestatefulsetspectemplatespecwithinitcontainers)
            * [`fn withInitContainersMixin(initContainers)`](#fn-specoverridestatefulsetspectemplatespecwithinitcontainersmixin)
            * [`fn withNodeName(nodeName)`](#fn-specoverridestatefulsetspectemplatespecwithnodename)
            * [`fn withNodeSelector(nodeSelector)`](#fn-specoverridestatefulsetspectemplatespecwithnodeselector)
            * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-specoverridestatefulsetspectemplatespecwithnodeselectormixin)
            * [`fn withOverhead(overhead)`](#fn-specoverridestatefulsetspectemplatespecwithoverhead)
            * [`fn withOverheadMixin(overhead)`](#fn-specoverridestatefulsetspectemplatespecwithoverheadmixin)
            * [`fn withPreemptionPolicy(preemptionPolicy)`](#fn-specoverridestatefulsetspectemplatespecwithpreemptionpolicy)
            * [`fn withPriority(priority)`](#fn-specoverridestatefulsetspectemplatespecwithpriority)
            * [`fn withPriorityClassName(priorityClassName)`](#fn-specoverridestatefulsetspectemplatespecwithpriorityclassname)
            * [`fn withReadinessGates(readinessGates)`](#fn-specoverridestatefulsetspectemplatespecwithreadinessgates)
            * [`fn withReadinessGatesMixin(readinessGates)`](#fn-specoverridestatefulsetspectemplatespecwithreadinessgatesmixin)
            * [`fn withRestartPolicy(restartPolicy)`](#fn-specoverridestatefulsetspectemplatespecwithrestartpolicy)
            * [`fn withRuntimeClassName(runtimeClassName)`](#fn-specoverridestatefulsetspectemplatespecwithruntimeclassname)
            * [`fn withSchedulerName(schedulerName)`](#fn-specoverridestatefulsetspectemplatespecwithschedulername)
            * [`fn withServiceAccount(serviceAccount)`](#fn-specoverridestatefulsetspectemplatespecwithserviceaccount)
            * [`fn withServiceAccountName(serviceAccountName)`](#fn-specoverridestatefulsetspectemplatespecwithserviceaccountname)
            * [`fn withSetHostnameAsFQDN(setHostnameAsFQDN)`](#fn-specoverridestatefulsetspectemplatespecwithsethostnameasfqdn)
            * [`fn withShareProcessNamespace(shareProcessNamespace)`](#fn-specoverridestatefulsetspectemplatespecwithshareprocessnamespace)
            * [`fn withSubdomain(subdomain)`](#fn-specoverridestatefulsetspectemplatespecwithsubdomain)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specoverridestatefulsetspectemplatespecwithterminationgraceperiodseconds)
            * [`fn withTolerations(tolerations)`](#fn-specoverridestatefulsetspectemplatespecwithtolerations)
            * [`fn withTolerationsMixin(tolerations)`](#fn-specoverridestatefulsetspectemplatespecwithtolerationsmixin)
            * [`fn withTopologySpreadConstraints(topologySpreadConstraints)`](#fn-specoverridestatefulsetspectemplatespecwithtopologyspreadconstraints)
            * [`fn withTopologySpreadConstraintsMixin(topologySpreadConstraints)`](#fn-specoverridestatefulsetspectemplatespecwithtopologyspreadconstraintsmixin)
            * [`fn withVolumes(volumes)`](#fn-specoverridestatefulsetspectemplatespecwithvolumes)
            * [`fn withVolumesMixin(volumes)`](#fn-specoverridestatefulsetspectemplatespecwithvolumesmixin)
            * [`obj spec.override.statefulSet.spec.template.spec.affinity`](#obj-specoverridestatefulsetspectemplatespecaffinity)
              * [`obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity`](#obj-specoverridestatefulsetspectemplatespecaffinitynodeaffinity)
                * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
                * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
                  * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
                  * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
              * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity`](#obj-specoverridestatefulsetspectemplatespecaffinitypodaffinity)
                * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
                * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
                * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
                * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
              * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity`](#obj-specoverridestatefulsetspectemplatespecaffinitypodantiaffinity)
                * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
                * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
                * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
                * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
            * [`obj spec.override.statefulSet.spec.template.spec.dnsConfig`](#obj-specoverridestatefulsetspectemplatespecdnsconfig)
              * [`fn withNameservers(nameservers)`](#fn-specoverridestatefulsetspectemplatespecdnsconfigwithnameservers)
              * [`fn withNameserversMixin(nameservers)`](#fn-specoverridestatefulsetspectemplatespecdnsconfigwithnameserversmixin)
              * [`fn withOptions(options)`](#fn-specoverridestatefulsetspectemplatespecdnsconfigwithoptions)
              * [`fn withOptionsMixin(options)`](#fn-specoverridestatefulsetspectemplatespecdnsconfigwithoptionsmixin)
              * [`fn withSearches(searches)`](#fn-specoverridestatefulsetspectemplatespecdnsconfigwithsearches)
              * [`fn withSearchesMixin(searches)`](#fn-specoverridestatefulsetspectemplatespecdnsconfigwithsearchesmixin)
            * [`obj spec.override.statefulSet.spec.template.spec.securityContext`](#obj-specoverridestatefulsetspectemplatespecsecuritycontext)
              * [`fn withFsGroup(fsGroup)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithfsgroup)
              * [`fn withFsGroupChangePolicy(fsGroupChangePolicy)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithfsgroupchangepolicy)
              * [`fn withRunAsGroup(runAsGroup)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithrunasgroup)
              * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithrunasnonroot)
              * [`fn withRunAsUser(runAsUser)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithrunasuser)
              * [`fn withSupplementalGroups(supplementalGroups)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithsupplementalgroups)
              * [`fn withSupplementalGroupsMixin(supplementalGroups)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithsupplementalgroupsmixin)
              * [`fn withSysctls(sysctls)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithsysctls)
              * [`fn withSysctlsMixin(sysctls)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithsysctlsmixin)
              * [`obj spec.override.statefulSet.spec.template.spec.securityContext.seLinuxOptions`](#obj-specoverridestatefulsetspectemplatespecsecuritycontextselinuxoptions)
                * [`fn withLevel(level)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextselinuxoptionswithlevel)
                * [`fn withRole(role)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextselinuxoptionswithrole)
                * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextselinuxoptionswithtype)
                * [`fn withUser(user)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextselinuxoptionswithuser)
              * [`obj spec.override.statefulSet.spec.template.spec.securityContext.seccompProfile`](#obj-specoverridestatefulsetspectemplatespecsecuritycontextseccompprofile)
                * [`fn withLocalhostProfile(localhostProfile)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextseccompprofilewithlocalhostprofile)
                * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextseccompprofilewithtype)
              * [`obj spec.override.statefulSet.spec.template.spec.securityContext.windowsOptions`](#obj-specoverridestatefulsetspectemplatespecsecuritycontextwindowsoptions)
                * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwindowsoptionswithgmsacredentialspec)
                * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwindowsoptionswithgmsacredentialspecname)
                * [`fn withRunAsUserName(runAsUserName)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwindowsoptionswithrunasusername)
        * [`obj spec.override.statefulSet.spec.updateStrategy`](#obj-specoverridestatefulsetspecupdatestrategy)
          * [`fn withType(type)`](#fn-specoverridestatefulsetspecupdatestrategywithtype)
          * [`obj spec.override.statefulSet.spec.updateStrategy.rollingUpdate`](#obj-specoverridestatefulsetspecupdatestrategyrollingupdate)
            * [`fn withPartition(partition)`](#fn-specoverridestatefulsetspecupdatestrategyrollingupdatewithpartition)
  * [`obj spec.persistence`](#obj-specpersistence)
    * [`fn withStorage(storage)`](#fn-specpersistencewithstorage)
    * [`fn withStorageClassName(storageClassName)`](#fn-specpersistencewithstorageclassname)
  * [`obj spec.rabbitmq`](#obj-specrabbitmq)
    * [`fn withAdditionalConfig(additionalConfig)`](#fn-specrabbitmqwithadditionalconfig)
    * [`fn withAdditionalPlugins(additionalPlugins)`](#fn-specrabbitmqwithadditionalplugins)
    * [`fn withAdditionalPluginsMixin(additionalPlugins)`](#fn-specrabbitmqwithadditionalpluginsmixin)
    * [`fn withAdvancedConfig(advancedConfig)`](#fn-specrabbitmqwithadvancedconfig)
    * [`fn withEnvConfig(envConfig)`](#fn-specrabbitmqwithenvconfig)
  * [`obj spec.resources`](#obj-specresources)
    * [`fn withLimits(limits)`](#fn-specresourceswithlimits)
    * [`fn withLimitsMixin(limits)`](#fn-specresourceswithlimitsmixin)
    * [`fn withRequests(requests)`](#fn-specresourceswithrequests)
    * [`fn withRequestsMixin(requests)`](#fn-specresourceswithrequestsmixin)
  * [`obj spec.service`](#obj-specservice)
    * [`fn withAnnotations(annotations)`](#fn-specservicewithannotations)
    * [`fn withAnnotationsMixin(annotations)`](#fn-specservicewithannotationsmixin)
    * [`fn withType(type)`](#fn-specservicewithtype)
  * [`obj spec.tls`](#obj-spectls)
    * [`fn withCaSecretName(caSecretName)`](#fn-spectlswithcasecretname)
    * [`fn withDisableNonTLSListeners(disableNonTLSListeners)`](#fn-spectlswithdisablenontlslisteners)
    * [`fn withSecretName(secretName)`](#fn-spectlswithsecretname)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of RabbitmqCluster

## obj metadata

"ObjectMeta is metadata that all persisted resources must have, which includes all objects users must create."

### fn metadata.withAnnotations

```ts
withAnnotations(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

### fn metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

**Note:** This function appends passed data to existing values

### fn metadata.withClusterName

```ts
withClusterName(clusterName)
```

"The name of the cluster which the object belongs to. This is used to distinguish resources with same name and namespace in different clusters. This field is not set anywhere right now and apiserver is going to ignore it if set in create or update request."

### fn metadata.withCreationTimestamp

```ts
withCreationTimestamp(creationTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withDeletionGracePeriodSeconds

```ts
withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)
```

"Number of seconds allowed for this object to gracefully terminate before it will be removed from the system. Only set when deletionTimestamp is also set. May only be shortened. Read-only."

### fn metadata.withDeletionTimestamp

```ts
withDeletionTimestamp(deletionTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withFinalizers

```ts
withFinalizers(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

### fn metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

**Note:** This function appends passed data to existing values

### fn metadata.withGenerateName

```ts
withGenerateName(generateName)
```

"GenerateName is an optional prefix, used by the server, to generate a unique name ONLY IF the Name field has not been provided. If this field is used, the name returned to the client will be different than the name passed. This value will also be combined with a unique suffix. The provided value has the same validation rules as the Name field, and may be truncated by the length of the suffix required to make the value unique on the server.\n\nIf this field is specified and the generated name exists, the server will NOT return a 409 - instead, it will either return 201 Created or 500 with Reason ServerTimeout indicating a unique name could not be found in the time allotted, and the client should retry (optionally after the time indicated in the Retry-After header).\n\nApplied only if Name is not specified. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#idempotency"

### fn metadata.withGeneration

```ts
withGeneration(generation)
```

"A sequence number representing a specific generation of the desired state. Populated by the system. Read-only."

### fn metadata.withLabels

```ts
withLabels(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

### fn metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

**Note:** This function appends passed data to existing values

### fn metadata.withManagedFields

```ts
withManagedFields(managedFields)
```

"ManagedFields maps workflow-id and version to the set of fields that are managed by that workflow. This is mostly for internal housekeeping, and users typically shouldn't need to set or understand this field. A workflow can be the user's name, a controller's name, or the name of a specific apply path like \"ci-cd\". The set of fields is always in the version that the workflow used when modifying the object."

### fn metadata.withManagedFieldsMixin

```ts
withManagedFieldsMixin(managedFields)
```

"ManagedFields maps workflow-id and version to the set of fields that are managed by that workflow. This is mostly for internal housekeeping, and users typically shouldn't need to set or understand this field. A workflow can be the user's name, a controller's name, or the name of a specific apply path like \"ci-cd\". The set of fields is always in the version that the workflow used when modifying the object."

**Note:** This function appends passed data to existing values

### fn metadata.withName

```ts
withName(name)
```

"Name must be unique within a namespace. Is required when creating resources, although some resources may allow a client to request the generation of an appropriate name automatically. Name is primarily intended for creation idempotence and configuration definition. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/identifiers#names"

### fn metadata.withNamespace

```ts
withNamespace(namespace)
```

"Namespace defines the space within which each name must be unique. An empty namespace is equivalent to the \"default\" namespace, but \"default\" is the canonical representation. Not all objects are required to be scoped to a namespace - the value of this field for those objects will be empty.\n\nMust be a DNS_LABEL. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/namespaces"

### fn metadata.withOwnerReferences

```ts
withOwnerReferences(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

### fn metadata.withOwnerReferencesMixin

```ts
withOwnerReferencesMixin(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

**Note:** This function appends passed data to existing values

### fn metadata.withResourceVersion

```ts
withResourceVersion(resourceVersion)
```

"An opaque value that represents the internal version of this object that can be used by clients to determine when objects have changed. May be used for optimistic concurrency, change detection, and the watch operation on a resource or set of resources. Clients must treat these values as opaque and passed unmodified back to the server. They may only be valid for a particular resource or set of resources.\n\nPopulated by the system. Read-only. Value must be treated as opaque by clients and . More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#concurrency-control-and-consistency"

### fn metadata.withSelfLink

```ts
withSelfLink(selfLink)
```

"SelfLink is a URL representing this object. Populated by the system. Read-only.\n\nDEPRECATED Kubernetes will stop propagating this field in 1.20 release and the field is planned to be removed in 1.21 release."

### fn metadata.withUid

```ts
withUid(uid)
```

"UID is the unique in time and space value for this object. It is typically generated by the server on successful creation of a resource and is not allowed to change on PUT operations.\n\nPopulated by the system. Read-only. More info: http://kubernetes.io/docs/user-guide/identifiers#uids"

## obj spec

"Spec is the desired state of the RabbitmqCluster Custom Resource."

### fn spec.withImage

```ts
withImage(image)
```

"Image is the name of the RabbitMQ docker image to use for RabbitMQ nodes in the RabbitmqCluster. Must be provided together with ImagePullSecrets in order to use an image in a private registry."

### fn spec.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```

"List of Secret resource containing access credentials to the registry for the RabbitMQ image. Required if the docker registry is private."

### fn spec.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```

"List of Secret resource containing access credentials to the registry for the RabbitMQ image. Required if the docker registry is private."

**Note:** This function appends passed data to existing values

### fn spec.withReplicas

```ts
withReplicas(replicas)
```

"Replicas is the number of nodes in the RabbitMQ cluster. Each node is deployed as a Replica in a StatefulSet. Only 1, 3, 5 replicas clusters are tested. This value should be an odd number to ensure the resultant cluster can establish exactly one quorum of nodes in the event of a fragmenting network partition."

### fn spec.withSkipPostDeploySteps

```ts
withSkipPostDeploySteps(skipPostDeploySteps)
```

"If unset, or set to false, the cluster will run `rabbitmq-queues rebalance all` whenever the cluster is updated. Set to true to prevent the operator rebalancing queue leaders after a cluster update. Has no effect if the cluster only consists of one node. For more information, see https://www.rabbitmq.com/rabbitmq-queues.8.html#rebalance"

### fn spec.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```

"TerminationGracePeriodSeconds is the timeout that each rabbitmqcluster pod will have to terminate gracefully. It defaults to 604800 seconds ( a week long) to ensure that the container preStop lifecycle hook can finish running. For more information, see: https://github.com/rabbitmq/cluster-operator/blob/main/docs/design/20200520-graceful-pod-termination.md"

### fn spec.withTolerations

```ts
withTolerations(tolerations)
```

"Tolerations is the list of Toleration resources attached to each Pod in the RabbitmqCluster."

### fn spec.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```

"Tolerations is the list of Toleration resources attached to each Pod in the RabbitmqCluster."

**Note:** This function appends passed data to existing values

## obj spec.affinity

"Affinity scheduling rules to be applied on created Pods."

## obj spec.affinity.nodeAffinity

"Describes node affinity scheduling rules for the pod."

### fn spec.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy the affinity expressions specified by this field, but it may choose a node that violates one or more of the expressions. The node that is most preferred is the one with the greatest sum of weights, i.e. for each node that meets all of the scheduling requirements (resource request, requiredDuringScheduling affinity expressions, etc.), compute a sum by iterating through the elements of this field and adding \"weight\" to the sum if the node matches the corresponding matchExpressions; the node(s) with the highest sum are the most preferred."

### fn spec.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy the affinity expressions specified by this field, but it may choose a node that violates one or more of the expressions. The node that is most preferred is the one with the greatest sum of weights, i.e. for each node that meets all of the scheduling requirements (resource request, requiredDuringScheduling affinity expressions, etc.), compute a sum by iterating through the elements of this field and adding \"weight\" to the sum if the node matches the corresponding matchExpressions; the node(s) with the highest sum are the most preferred."

**Note:** This function appends passed data to existing values

## obj spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution

"If the affinity requirements specified by this field are not met at scheduling time, the pod will not be scheduled onto the node. If the affinity requirements specified by this field cease to be met at some point during pod execution (e.g. due to an update), the system may or may not try to eventually evict the pod from its node."

### fn spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```

"Required. A list of node selector terms. The terms are ORed."

### fn spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```

"Required. A list of node selector terms. The terms are ORed."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAffinity

"Describes pod affinity scheduling rules (e.g. co-locate this pod in the same node, zone, etc. as some other pod(s))."

### fn spec.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy the affinity expressions specified by this field, but it may choose a node that violates one or more of the expressions. The node that is most preferred is the one with the greatest sum of weights, i.e. for each node that meets all of the scheduling requirements (resource request, requiredDuringScheduling affinity expressions, etc.), compute a sum by iterating through the elements of this field and adding \"weight\" to the sum if the node has pods which matches the corresponding podAffinityTerm; the node(s) with the highest sum are the most preferred."

### fn spec.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy the affinity expressions specified by this field, but it may choose a node that violates one or more of the expressions. The node that is most preferred is the one with the greatest sum of weights, i.e. for each node that meets all of the scheduling requirements (resource request, requiredDuringScheduling affinity expressions, etc.), compute a sum by iterating through the elements of this field and adding \"weight\" to the sum if the node has pods which matches the corresponding podAffinityTerm; the node(s) with the highest sum are the most preferred."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```

"If the affinity requirements specified by this field are not met at scheduling time, the pod will not be scheduled onto the node. If the affinity requirements specified by this field cease to be met at some point during pod execution (e.g. due to a pod label update), the system may or may not try to eventually evict the pod from its node. When there are multiple elements, the lists of nodes corresponding to each podAffinityTerm are intersected, i.e. all terms must be satisfied."

### fn spec.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```

"If the affinity requirements specified by this field are not met at scheduling time, the pod will not be scheduled onto the node. If the affinity requirements specified by this field cease to be met at some point during pod execution (e.g. due to a pod label update), the system may or may not try to eventually evict the pod from its node. When there are multiple elements, the lists of nodes corresponding to each podAffinityTerm are intersected, i.e. all terms must be satisfied."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAntiAffinity

"Describes pod anti-affinity scheduling rules (e.g. avoid putting this pod in the same node, zone, etc. as some other pod(s))."

### fn spec.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy the anti-affinity expressions specified by this field, but it may choose a node that violates one or more of the expressions. The node that is most preferred is the one with the greatest sum of weights, i.e. for each node that meets all of the scheduling requirements (resource request, requiredDuringScheduling anti-affinity expressions, etc.), compute a sum by iterating through the elements of this field and adding \"weight\" to the sum if the node has pods which matches the corresponding podAffinityTerm; the node(s) with the highest sum are the most preferred."

### fn spec.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy the anti-affinity expressions specified by this field, but it may choose a node that violates one or more of the expressions. The node that is most preferred is the one with the greatest sum of weights, i.e. for each node that meets all of the scheduling requirements (resource request, requiredDuringScheduling anti-affinity expressions, etc.), compute a sum by iterating through the elements of this field and adding \"weight\" to the sum if the node has pods which matches the corresponding podAffinityTerm; the node(s) with the highest sum are the most preferred."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```

"If the anti-affinity requirements specified by this field are not met at scheduling time, the pod will not be scheduled onto the node. If the anti-affinity requirements specified by this field cease to be met at some point during pod execution (e.g. due to a pod label update), the system may or may not try to eventually evict the pod from its node. When there are multiple elements, the lists of nodes corresponding to each podAffinityTerm are intersected, i.e. all terms must be satisfied."

### fn spec.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```

"If the anti-affinity requirements specified by this field are not met at scheduling time, the pod will not be scheduled onto the node. If the anti-affinity requirements specified by this field cease to be met at some point during pod execution (e.g. due to a pod label update), the system may or may not try to eventually evict the pod from its node. When there are multiple elements, the lists of nodes corresponding to each podAffinityTerm are intersected, i.e. all terms must be satisfied."

**Note:** This function appends passed data to existing values

## obj spec.override



## obj spec.override.service



## obj spec.override.service.metadata



### fn spec.override.service.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.override.service.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.override.service.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.override.service.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.service.spec



### fn spec.override.service.spec.withAllocateLoadBalancerNodePorts

```ts
withAllocateLoadBalancerNodePorts(allocateLoadBalancerNodePorts)
```



### fn spec.override.service.spec.withClusterIP

```ts
withClusterIP(clusterIP)
```



### fn spec.override.service.spec.withClusterIPs

```ts
withClusterIPs(clusterIPs)
```



### fn spec.override.service.spec.withClusterIPsMixin

```ts
withClusterIPsMixin(clusterIPs)
```



**Note:** This function appends passed data to existing values

### fn spec.override.service.spec.withExternalIPs

```ts
withExternalIPs(externalIPs)
```



### fn spec.override.service.spec.withExternalIPsMixin

```ts
withExternalIPsMixin(externalIPs)
```



**Note:** This function appends passed data to existing values

### fn spec.override.service.spec.withExternalName

```ts
withExternalName(externalName)
```



### fn spec.override.service.spec.withExternalTrafficPolicy

```ts
withExternalTrafficPolicy(externalTrafficPolicy)
```



### fn spec.override.service.spec.withHealthCheckNodePort

```ts
withHealthCheckNodePort(healthCheckNodePort)
```



### fn spec.override.service.spec.withIpFamilies

```ts
withIpFamilies(ipFamilies)
```



### fn spec.override.service.spec.withIpFamiliesMixin

```ts
withIpFamiliesMixin(ipFamilies)
```



**Note:** This function appends passed data to existing values

### fn spec.override.service.spec.withIpFamilyPolicy

```ts
withIpFamilyPolicy(ipFamilyPolicy)
```



### fn spec.override.service.spec.withLoadBalancerIP

```ts
withLoadBalancerIP(loadBalancerIP)
```



### fn spec.override.service.spec.withLoadBalancerSourceRanges

```ts
withLoadBalancerSourceRanges(loadBalancerSourceRanges)
```



### fn spec.override.service.spec.withLoadBalancerSourceRangesMixin

```ts
withLoadBalancerSourceRangesMixin(loadBalancerSourceRanges)
```



**Note:** This function appends passed data to existing values

### fn spec.override.service.spec.withPorts

```ts
withPorts(ports)
```



### fn spec.override.service.spec.withPortsMixin

```ts
withPortsMixin(ports)
```



**Note:** This function appends passed data to existing values

### fn spec.override.service.spec.withPublishNotReadyAddresses

```ts
withPublishNotReadyAddresses(publishNotReadyAddresses)
```



### fn spec.override.service.spec.withSelector

```ts
withSelector(selector)
```



### fn spec.override.service.spec.withSelectorMixin

```ts
withSelectorMixin(selector)
```



**Note:** This function appends passed data to existing values

### fn spec.override.service.spec.withSessionAffinity

```ts
withSessionAffinity(sessionAffinity)
```



### fn spec.override.service.spec.withTopologyKeys

```ts
withTopologyKeys(topologyKeys)
```



### fn spec.override.service.spec.withTopologyKeysMixin

```ts
withTopologyKeysMixin(topologyKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.override.service.spec.withType

```ts
withType(type)
```



## obj spec.override.service.spec.sessionAffinityConfig



## obj spec.override.service.spec.sessionAffinityConfig.clientIP



### fn spec.override.service.spec.sessionAffinityConfig.clientIP.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.override.statefulSet



## obj spec.override.statefulSet.metadata



### fn spec.override.statefulSet.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.override.statefulSet.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.override.statefulSet.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec



### fn spec.override.statefulSet.spec.withPodManagementPolicy

```ts
withPodManagementPolicy(podManagementPolicy)
```



### fn spec.override.statefulSet.spec.withReplicas

```ts
withReplicas(replicas)
```



### fn spec.override.statefulSet.spec.withServiceName

```ts
withServiceName(serviceName)
```



### fn spec.override.statefulSet.spec.withVolumeClaimTemplates

```ts
withVolumeClaimTemplates(volumeClaimTemplates)
```



### fn spec.override.statefulSet.spec.withVolumeClaimTemplatesMixin

```ts
withVolumeClaimTemplatesMixin(volumeClaimTemplates)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.selector



### fn spec.override.statefulSet.spec.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.override.statefulSet.spec.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template



## obj spec.override.statefulSet.spec.template.metadata



### fn spec.override.statefulSet.spec.template.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.override.statefulSet.spec.template.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.override.statefulSet.spec.template.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.metadata.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.metadata.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.override.statefulSet.spec.template.spec



### fn spec.override.statefulSet.spec.template.spec.withActiveDeadlineSeconds

```ts
withActiveDeadlineSeconds(activeDeadlineSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.withAutomountServiceAccountToken

```ts
withAutomountServiceAccountToken(automountServiceAccountToken)
```



### fn spec.override.statefulSet.spec.template.spec.withContainers

```ts
withContainers(containers)
```



### fn spec.override.statefulSet.spec.template.spec.withContainersMixin

```ts
withContainersMixin(containers)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.withDnsPolicy

```ts
withDnsPolicy(dnsPolicy)
```



### fn spec.override.statefulSet.spec.template.spec.withEnableServiceLinks

```ts
withEnableServiceLinks(enableServiceLinks)
```



### fn spec.override.statefulSet.spec.template.spec.withEphemeralContainers

```ts
withEphemeralContainers(ephemeralContainers)
```



### fn spec.override.statefulSet.spec.template.spec.withEphemeralContainersMixin

```ts
withEphemeralContainersMixin(ephemeralContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.withHostAliases

```ts
withHostAliases(hostAliases)
```



### fn spec.override.statefulSet.spec.template.spec.withHostAliasesMixin

```ts
withHostAliasesMixin(hostAliases)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.withHostIPC

```ts
withHostIPC(hostIPC)
```



### fn spec.override.statefulSet.spec.template.spec.withHostNetwork

```ts
withHostNetwork(hostNetwork)
```



### fn spec.override.statefulSet.spec.template.spec.withHostPID

```ts
withHostPID(hostPID)
```



### fn spec.override.statefulSet.spec.template.spec.withHostname

```ts
withHostname(hostname)
```



### fn spec.override.statefulSet.spec.template.spec.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.override.statefulSet.spec.template.spec.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.override.statefulSet.spec.template.spec.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.withNodeName

```ts
withNodeName(nodeName)
```



### fn spec.override.statefulSet.spec.template.spec.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.override.statefulSet.spec.template.spec.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.withOverhead

```ts
withOverhead(overhead)
```



### fn spec.override.statefulSet.spec.template.spec.withOverheadMixin

```ts
withOverheadMixin(overhead)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.withPreemptionPolicy

```ts
withPreemptionPolicy(preemptionPolicy)
```



### fn spec.override.statefulSet.spec.template.spec.withPriority

```ts
withPriority(priority)
```



### fn spec.override.statefulSet.spec.template.spec.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.override.statefulSet.spec.template.spec.withReadinessGates

```ts
withReadinessGates(readinessGates)
```



### fn spec.override.statefulSet.spec.template.spec.withReadinessGatesMixin

```ts
withReadinessGatesMixin(readinessGates)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



### fn spec.override.statefulSet.spec.template.spec.withRuntimeClassName

```ts
withRuntimeClassName(runtimeClassName)
```



### fn spec.override.statefulSet.spec.template.spec.withSchedulerName

```ts
withSchedulerName(schedulerName)
```



### fn spec.override.statefulSet.spec.template.spec.withServiceAccount

```ts
withServiceAccount(serviceAccount)
```



### fn spec.override.statefulSet.spec.template.spec.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.override.statefulSet.spec.template.spec.withSetHostnameAsFQDN

```ts
withSetHostnameAsFQDN(setHostnameAsFQDN)
```



### fn spec.override.statefulSet.spec.template.spec.withShareProcessNamespace

```ts
withShareProcessNamespace(shareProcessNamespace)
```



### fn spec.override.statefulSet.spec.template.spec.withSubdomain

```ts
withSubdomain(subdomain)
```



### fn spec.override.statefulSet.spec.template.spec.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.override.statefulSet.spec.template.spec.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.withTopologySpreadConstraints

```ts
withTopologySpreadConstraints(topologySpreadConstraints)
```



### fn spec.override.statefulSet.spec.template.spec.withTopologySpreadConstraintsMixin

```ts
withTopologySpreadConstraintsMixin(topologySpreadConstraints)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.override.statefulSet.spec.template.spec.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity



## obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.dnsConfig



### fn spec.override.statefulSet.spec.template.spec.dnsConfig.withNameservers

```ts
withNameservers(nameservers)
```



### fn spec.override.statefulSet.spec.template.spec.dnsConfig.withNameserversMixin

```ts
withNameserversMixin(nameservers)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.dnsConfig.withOptions

```ts
withOptions(options)
```



### fn spec.override.statefulSet.spec.template.spec.dnsConfig.withOptionsMixin

```ts
withOptionsMixin(options)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.dnsConfig.withSearches

```ts
withSearches(searches)
```



### fn spec.override.statefulSet.spec.template.spec.dnsConfig.withSearchesMixin

```ts
withSearchesMixin(searches)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.securityContext



### fn spec.override.statefulSet.spec.template.spec.securityContext.withFsGroup

```ts
withFsGroup(fsGroup)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.withFsGroupChangePolicy

```ts
withFsGroupChangePolicy(fsGroupChangePolicy)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.withSupplementalGroups

```ts
withSupplementalGroups(supplementalGroups)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.withSupplementalGroupsMixin

```ts
withSupplementalGroupsMixin(supplementalGroups)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.securityContext.withSysctls

```ts
withSysctls(sysctls)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.withSysctlsMixin

```ts
withSysctlsMixin(sysctls)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.securityContext.seLinuxOptions



### fn spec.override.statefulSet.spec.template.spec.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.override.statefulSet.spec.template.spec.securityContext.seccompProfile



### fn spec.override.statefulSet.spec.template.spec.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.override.statefulSet.spec.template.spec.securityContext.windowsOptions



### fn spec.override.statefulSet.spec.template.spec.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.override.statefulSet.spec.updateStrategy



### fn spec.override.statefulSet.spec.updateStrategy.withType

```ts
withType(type)
```



## obj spec.override.statefulSet.spec.updateStrategy.rollingUpdate



### fn spec.override.statefulSet.spec.updateStrategy.rollingUpdate.withPartition

```ts
withPartition(partition)
```



## obj spec.persistence

"The desired persistent storage configuration for each Pod in the cluster."

### fn spec.persistence.withStorage

```ts
withStorage(storage)
```

"The requested size of the persistent volume attached to each Pod in the RabbitmqCluster. The format of this field matches that defined by kubernetes/apimachinery. See https://pkg.go.dev/k8s.io/apimachinery/pkg/api/resource#Quantity for more info on the format of this field."

### fn spec.persistence.withStorageClassName

```ts
withStorageClassName(storageClassName)
```

"The name of the StorageClass to claim a PersistentVolume from."

## obj spec.rabbitmq

"Configuration options for RabbitMQ Pods created in the cluster."

### fn spec.rabbitmq.withAdditionalConfig

```ts
withAdditionalConfig(additionalConfig)
```

"Modify to add to the rabbitmq.conf file in addition to default configurations set by the operator. Modifying this property on an existing RabbitmqCluster will trigger a StatefulSet rolling restart and will cause rabbitmq downtime. For more information on this config, see https://www.rabbitmq.com/configure.html#config-file"

### fn spec.rabbitmq.withAdditionalPlugins

```ts
withAdditionalPlugins(additionalPlugins)
```

"List of plugins to enable in addition to essential plugins: rabbitmq_management, rabbitmq_prometheus, and rabbitmq_peer_discovery_k8s."

### fn spec.rabbitmq.withAdditionalPluginsMixin

```ts
withAdditionalPluginsMixin(additionalPlugins)
```

"List of plugins to enable in addition to essential plugins: rabbitmq_management, rabbitmq_prometheus, and rabbitmq_peer_discovery_k8s."

**Note:** This function appends passed data to existing values

### fn spec.rabbitmq.withAdvancedConfig

```ts
withAdvancedConfig(advancedConfig)
```

"Specify any rabbitmq advanced.config configurations to apply to the cluster. For more information on advanced config, see https://www.rabbitmq.com/configure.html#advanced-config-file"

### fn spec.rabbitmq.withEnvConfig

```ts
withEnvConfig(envConfig)
```

"Modify to add to the rabbitmq-env.conf file. Modifying this property on an existing RabbitmqCluster will trigger a StatefulSet rolling restart and will cause rabbitmq downtime. For more information on env config, see https://www.rabbitmq.com/man/rabbitmq-env.conf.5.html"

## obj spec.resources

"The desired compute resource requirements of Pods in the cluster."

### fn spec.resources.withLimits

```ts
withLimits(limits)
```

"Limits describes the maximum amount of compute resources allowed. More info: https://kubernetes.io/docs/concepts/configuration/manage-compute-resources-container/"

### fn spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```

"Limits describes the maximum amount of compute resources allowed. More info: https://kubernetes.io/docs/concepts/configuration/manage-compute-resources-container/"

**Note:** This function appends passed data to existing values

### fn spec.resources.withRequests

```ts
withRequests(requests)
```

"Requests describes the minimum amount of compute resources required. If Requests is omitted for a container, it defaults to Limits if that is explicitly specified, otherwise to an implementation-defined value. More info: https://kubernetes.io/docs/concepts/configuration/manage-compute-resources-container/"

### fn spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```

"Requests describes the minimum amount of compute resources required. If Requests is omitted for a container, it defaults to Limits if that is explicitly specified, otherwise to an implementation-defined value. More info: https://kubernetes.io/docs/concepts/configuration/manage-compute-resources-container/"

**Note:** This function appends passed data to existing values

## obj spec.service

"The desired state of the Kubernetes Service to create for the cluster."

### fn spec.service.withAnnotations

```ts
withAnnotations(annotations)
```

"Annotations to add to the Service."

### fn spec.service.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Annotations to add to the Service."

**Note:** This function appends passed data to existing values

### fn spec.service.withType

```ts
withType(type)
```

"Type of Service to create for the cluster. Must be one of: ClusterIP, LoadBalancer, NodePort. For more info see https://pkg.go.dev/k8s.io/api/core/v1#ServiceType"

## obj spec.tls

"TLS-related configuration for the RabbitMQ cluster."

### fn spec.tls.withCaSecretName

```ts
withCaSecretName(caSecretName)
```

"Name of a Secret in the same Namespace as the RabbitmqCluster, containing the Certificate Authority's public certificate for TLS. The Secret must store this as ca.crt. This Secret can be created by running `kubectl create secret generic ca-secret --from-file=ca.crt=path/to/ca.cert` Used for mTLS, and TLS for rabbitmq_web_stomp and rabbitmq_web_mqtt."

### fn spec.tls.withDisableNonTLSListeners

```ts
withDisableNonTLSListeners(disableNonTLSListeners)
```

"When set to true, the RabbitmqCluster disables non-TLS listeners for RabbitMQ, management plugin and for any enabled plugins in the following list: stomp, mqtt, web_stomp, web_mqtt. Only TLS-enabled clients will be able to connect."

### fn spec.tls.withSecretName

```ts
withSecretName(secretName)
```

"Name of a Secret in the same Namespace as the RabbitmqCluster, containing the server's private key & public certificate for TLS. The Secret must store these as tls.key and tls.crt, respectively. This Secret can be created by running `kubectl create secret tls tls-secret --cert=path/to/tls.cert --key=path/to/tls.key`"