---
permalink: /2.14/rabbitmq/v1beta1/rabbitmqCluster/
---

# rabbitmq.v1beta1.rabbitmqCluster

"RabbitmqCluster is the Schema for the RabbitmqCluster API. Each instance of this object\ncorresponds to a single RabbitMQ cluster."

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
  * [`fn withName(name)`](#fn-metadatawithname)
  * [`fn withNamespace(namespace)`](#fn-metadatawithnamespace)
  * [`fn withOwnerReferences(ownerReferences)`](#fn-metadatawithownerreferences)
  * [`fn withOwnerReferencesMixin(ownerReferences)`](#fn-metadatawithownerreferencesmixin)
  * [`fn withResourceVersion(resourceVersion)`](#fn-metadatawithresourceversion)
  * [`fn withSelfLink(selfLink)`](#fn-metadatawithselflink)
  * [`fn withUid(uid)`](#fn-metadatawithuid)
* [`obj spec`](#obj-spec)
  * [`fn withDelayStartSeconds(delayStartSeconds)`](#fn-specwithdelaystartseconds)
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
      * [`obj spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
        * [`fn withWeight(weight)`](#fn-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
        * [`obj spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
          * [`fn withMatchExpressions(matchExpressions)`](#fn-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
          * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
          * [`fn withMatchFields(matchFields)`](#fn-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
          * [`fn withMatchFieldsMixin(matchFields)`](#fn-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
          * [`obj spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
            * [`fn withKey(key)`](#fn-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
            * [`fn withOperator(operator)`](#fn-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
            * [`fn withValues(values)`](#fn-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
          * [`obj spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
            * [`fn withKey(key)`](#fn-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
            * [`fn withOperator(operator)`](#fn-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
            * [`fn withValues(values)`](#fn-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
      * [`obj spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
        * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
        * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
        * [`obj spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
          * [`fn withMatchExpressions(matchExpressions)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
          * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
          * [`fn withMatchFields(matchFields)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
          * [`fn withMatchFieldsMixin(matchFields)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
          * [`obj spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
            * [`fn withKey(key)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
            * [`fn withOperator(operator)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
            * [`fn withValues(values)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
          * [`obj spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
            * [`fn withKey(key)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
            * [`fn withOperator(operator)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
            * [`fn withValues(values)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
    * [`obj spec.affinity.podAffinity`](#obj-specaffinitypodaffinity)
      * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
      * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
      * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
      * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
      * [`obj spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
        * [`fn withWeight(weight)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
        * [`obj spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
          * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
          * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
          * [`fn withNamespaces(namespaces)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
          * [`obj spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
            * [`obj spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
        * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
        * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
        * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
        * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
        * [`fn withNamespaces(namespaces)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
        * [`fn withNamespacesMixin(namespaces)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
        * [`fn withTopologyKey(topologyKey)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
        * [`obj spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
          * [`fn withMatchExpressions(matchExpressions)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
          * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
          * [`fn withMatchLabels(matchLabels)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
          * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
          * [`obj spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
            * [`fn withKey(key)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
            * [`fn withOperator(operator)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
            * [`fn withValues(values)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
        * [`obj spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
          * [`fn withMatchExpressions(matchExpressions)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
          * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
          * [`fn withMatchLabels(matchLabels)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
          * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
          * [`obj spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
            * [`fn withKey(key)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
            * [`fn withOperator(operator)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
            * [`fn withValues(values)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
    * [`obj spec.affinity.podAntiAffinity`](#obj-specaffinitypodantiaffinity)
      * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
      * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
      * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
      * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
      * [`obj spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
        * [`fn withWeight(weight)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
        * [`obj spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
          * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
          * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
          * [`fn withNamespaces(namespaces)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
          * [`obj spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
            * [`obj spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
        * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
        * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
        * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
        * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
        * [`fn withNamespaces(namespaces)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
        * [`fn withNamespacesMixin(namespaces)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
        * [`fn withTopologyKey(topologyKey)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
        * [`obj spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
          * [`fn withMatchExpressions(matchExpressions)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
          * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
          * [`fn withMatchLabels(matchLabels)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
          * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
          * [`obj spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
            * [`fn withKey(key)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
            * [`fn withOperator(operator)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
            * [`fn withValues(values)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
        * [`obj spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
          * [`fn withMatchExpressions(matchExpressions)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
          * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
          * [`fn withMatchLabels(matchLabels)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
          * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
          * [`obj spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
            * [`fn withKey(key)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
            * [`fn withOperator(operator)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
            * [`fn withValues(values)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
  * [`obj spec.imagePullSecrets`](#obj-specimagepullsecrets)
    * [`fn withName(name)`](#fn-specimagepullsecretswithname)
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
        * [`fn withInternalTrafficPolicy(internalTrafficPolicy)`](#fn-specoverrideservicespecwithinternaltrafficpolicy)
        * [`fn withIpFamilies(ipFamilies)`](#fn-specoverrideservicespecwithipfamilies)
        * [`fn withIpFamiliesMixin(ipFamilies)`](#fn-specoverrideservicespecwithipfamiliesmixin)
        * [`fn withIpFamilyPolicy(ipFamilyPolicy)`](#fn-specoverrideservicespecwithipfamilypolicy)
        * [`fn withLoadBalancerClass(loadBalancerClass)`](#fn-specoverrideservicespecwithloadbalancerclass)
        * [`fn withLoadBalancerIP(loadBalancerIP)`](#fn-specoverrideservicespecwithloadbalancerip)
        * [`fn withLoadBalancerSourceRanges(loadBalancerSourceRanges)`](#fn-specoverrideservicespecwithloadbalancersourceranges)
        * [`fn withLoadBalancerSourceRangesMixin(loadBalancerSourceRanges)`](#fn-specoverrideservicespecwithloadbalancersourcerangesmixin)
        * [`fn withPorts(ports)`](#fn-specoverrideservicespecwithports)
        * [`fn withPortsMixin(ports)`](#fn-specoverrideservicespecwithportsmixin)
        * [`fn withPublishNotReadyAddresses(publishNotReadyAddresses)`](#fn-specoverrideservicespecwithpublishnotreadyaddresses)
        * [`fn withSelector(selector)`](#fn-specoverrideservicespecwithselector)
        * [`fn withSelectorMixin(selector)`](#fn-specoverrideservicespecwithselectormixin)
        * [`fn withSessionAffinity(sessionAffinity)`](#fn-specoverrideservicespecwithsessionaffinity)
        * [`fn withTrafficDistribution(trafficDistribution)`](#fn-specoverrideservicespecwithtrafficdistribution)
        * [`fn withType(type)`](#fn-specoverrideservicespecwithtype)
        * [`obj spec.override.service.spec.ports`](#obj-specoverrideservicespecports)
          * [`fn withAppProtocol(appProtocol)`](#fn-specoverrideservicespecportswithappprotocol)
          * [`fn withName(name)`](#fn-specoverrideservicespecportswithname)
          * [`fn withNodePort(nodePort)`](#fn-specoverrideservicespecportswithnodeport)
          * [`fn withPort(port)`](#fn-specoverrideservicespecportswithport)
          * [`fn withProtocol(protocol)`](#fn-specoverrideservicespecportswithprotocol)
          * [`fn withTargetPort(targetPort)`](#fn-specoverrideservicespecportswithtargetport)
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
        * [`fn withMinReadySeconds(minReadySeconds)`](#fn-specoverridestatefulsetspecwithminreadyseconds)
        * [`fn withPodManagementPolicy(podManagementPolicy)`](#fn-specoverridestatefulsetspecwithpodmanagementpolicy)
        * [`fn withReplicas(replicas)`](#fn-specoverridestatefulsetspecwithreplicas)
        * [`fn withServiceName(serviceName)`](#fn-specoverridestatefulsetspecwithservicename)
        * [`fn withVolumeClaimTemplates(volumeClaimTemplates)`](#fn-specoverridestatefulsetspecwithvolumeclaimtemplates)
        * [`fn withVolumeClaimTemplatesMixin(volumeClaimTemplates)`](#fn-specoverridestatefulsetspecwithvolumeclaimtemplatesmixin)
        * [`obj spec.override.statefulSet.spec.persistentVolumeClaimRetentionPolicy`](#obj-specoverridestatefulsetspecpersistentvolumeclaimretentionpolicy)
          * [`fn withWhenDeleted(whenDeleted)`](#fn-specoverridestatefulsetspecpersistentvolumeclaimretentionpolicywithwhendeleted)
          * [`fn withWhenScaled(whenScaled)`](#fn-specoverridestatefulsetspecpersistentvolumeclaimretentionpolicywithwhenscaled)
        * [`obj spec.override.statefulSet.spec.selector`](#obj-specoverridestatefulsetspecselector)
          * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspecselectorwithmatchexpressions)
          * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspecselectorwithmatchexpressionsmixin)
          * [`fn withMatchLabels(matchLabels)`](#fn-specoverridestatefulsetspecselectorwithmatchlabels)
          * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specoverridestatefulsetspecselectorwithmatchlabelsmixin)
          * [`obj spec.override.statefulSet.spec.selector.matchExpressions`](#obj-specoverridestatefulsetspecselectormatchexpressions)
            * [`fn withKey(key)`](#fn-specoverridestatefulsetspecselectormatchexpressionswithkey)
            * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspecselectormatchexpressionswithoperator)
            * [`fn withValues(values)`](#fn-specoverridestatefulsetspecselectormatchexpressionswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspecselectormatchexpressionswithvaluesmixin)
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
            * [`fn withHostUsers(hostUsers)`](#fn-specoverridestatefulsetspectemplatespecwithhostusers)
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
            * [`fn withResourceClaims(resourceClaims)`](#fn-specoverridestatefulsetspectemplatespecwithresourceclaims)
            * [`fn withResourceClaimsMixin(resourceClaims)`](#fn-specoverridestatefulsetspectemplatespecwithresourceclaimsmixin)
            * [`fn withRestartPolicy(restartPolicy)`](#fn-specoverridestatefulsetspectemplatespecwithrestartpolicy)
            * [`fn withRuntimeClassName(runtimeClassName)`](#fn-specoverridestatefulsetspectemplatespecwithruntimeclassname)
            * [`fn withSchedulerName(schedulerName)`](#fn-specoverridestatefulsetspectemplatespecwithschedulername)
            * [`fn withSchedulingGates(schedulingGates)`](#fn-specoverridestatefulsetspectemplatespecwithschedulinggates)
            * [`fn withSchedulingGatesMixin(schedulingGates)`](#fn-specoverridestatefulsetspectemplatespecwithschedulinggatesmixin)
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
                * [`obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
                  * [`fn withWeight(weight)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
                  * [`obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
                    * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
                    * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
                    * [`fn withMatchFields(matchFields)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
                    * [`fn withMatchFieldsMixin(matchFields)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
                    * [`obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                      * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                      * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                      * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                      * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
                    * [`obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                      * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                      * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                      * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                      * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
                  * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
                  * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
                  * [`obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
                    * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
                    * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
                    * [`fn withMatchFields(matchFields)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
                    * [`fn withMatchFieldsMixin(matchFields)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
                    * [`obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                      * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                      * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                      * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                      * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
                    * [`obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                      * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                      * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                      * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                      * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
              * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity`](#obj-specoverridestatefulsetspectemplatespecaffinitypodaffinity)
                * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
                * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
                * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
                * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
                  * [`fn withWeight(weight)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
                  * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
                    * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
                    * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
                    * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
                    * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
                    * [`fn withNamespaces(namespaces)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
                    * [`fn withNamespacesMixin(namespaces)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
                    * [`fn withTopologyKey(topologyKey)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
                    * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                      * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                      * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                      * [`fn withMatchLabels(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                      * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                      * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                        * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                        * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                        * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                        * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
                    * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                      * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                      * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                      * [`fn withMatchLabels(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                      * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                      * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                        * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                        * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                        * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                        * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
                  * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
                  * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
                  * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
                  * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
                  * [`fn withNamespaces(namespaces)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
                  * [`fn withNamespacesMixin(namespaces)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
                  * [`fn withTopologyKey(topologyKey)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
                  * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
                    * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
                    * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
                    * [`fn withMatchLabels(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
                    * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
                    * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                      * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                      * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                      * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                      * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
                  * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
                    * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
                    * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
                    * [`fn withMatchLabels(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
                    * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
                    * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                      * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                      * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                      * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                      * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
              * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity`](#obj-specoverridestatefulsetspectemplatespecaffinitypodantiaffinity)
                * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
                * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
                * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
                * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
                  * [`fn withWeight(weight)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
                  * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
                    * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
                    * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
                    * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
                    * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
                    * [`fn withNamespaces(namespaces)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
                    * [`fn withNamespacesMixin(namespaces)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
                    * [`fn withTopologyKey(topologyKey)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
                    * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                      * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                      * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                      * [`fn withMatchLabels(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                      * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                      * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                        * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                        * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                        * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                        * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
                    * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                      * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                      * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                      * [`fn withMatchLabels(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                      * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                      * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                        * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                        * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                        * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                        * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
                  * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
                  * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
                  * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
                  * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
                  * [`fn withNamespaces(namespaces)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
                  * [`fn withNamespacesMixin(namespaces)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
                  * [`fn withTopologyKey(topologyKey)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
                  * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
                    * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
                    * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
                    * [`fn withMatchLabels(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
                    * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
                    * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                      * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                      * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                      * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                      * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
                  * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
                    * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
                    * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
                    * [`fn withMatchLabels(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
                    * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
                    * [`obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                      * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                      * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                      * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                      * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
            * [`obj spec.override.statefulSet.spec.template.spec.containers`](#obj-specoverridestatefulsetspectemplatespeccontainers)
              * [`fn withArgs(args)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithargs)
              * [`fn withArgsMixin(args)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithargsmixin)
              * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithcommand)
              * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithcommandmixin)
              * [`fn withEnv(env)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithenv)
              * [`fn withEnvFrom(envFrom)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithenvfrom)
              * [`fn withEnvFromMixin(envFrom)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithenvfrommixin)
              * [`fn withEnvMixin(env)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithenvmixin)
              * [`fn withImage(image)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithimage)
              * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithimagepullpolicy)
              * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithname)
              * [`fn withPorts(ports)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithports)
              * [`fn withPortsMixin(ports)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithportsmixin)
              * [`fn withResizePolicy(resizePolicy)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithresizepolicy)
              * [`fn withResizePolicyMixin(resizePolicy)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithresizepolicymixin)
              * [`fn withRestartPolicy(restartPolicy)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithrestartpolicy)
              * [`fn withStdin(stdin)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithstdin)
              * [`fn withStdinOnce(stdinOnce)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithstdinonce)
              * [`fn withTerminationMessagePath(terminationMessagePath)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithterminationmessagepath)
              * [`fn withTerminationMessagePolicy(terminationMessagePolicy)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithterminationmessagepolicy)
              * [`fn withTty(tty)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithtty)
              * [`fn withVolumeDevices(volumeDevices)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithvolumedevices)
              * [`fn withVolumeDevicesMixin(volumeDevices)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithvolumedevicesmixin)
              * [`fn withVolumeMounts(volumeMounts)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithvolumemounts)
              * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithvolumemountsmixin)
              * [`fn withWorkingDir(workingDir)`](#fn-specoverridestatefulsetspectemplatespeccontainerswithworkingdir)
              * [`obj spec.override.statefulSet.spec.template.spec.containers.env`](#obj-specoverridestatefulsetspectemplatespeccontainersenv)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvwithname)
                * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvwithvalue)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.env.valueFrom`](#obj-specoverridestatefulsetspectemplatespeccontainersenvvaluefrom)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.configMapKeyRef`](#obj-specoverridestatefulsetspectemplatespeccontainersenvvaluefromconfigmapkeyref)
                    * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvvaluefromconfigmapkeyrefwithkey)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvvaluefromconfigmapkeyrefwithname)
                    * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvvaluefromconfigmapkeyrefwithoptional)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.fieldRef`](#obj-specoverridestatefulsetspectemplatespeccontainersenvvaluefromfieldref)
                    * [`fn withApiVersion(apiVersion)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvvaluefromfieldrefwithapiversion)
                    * [`fn withFieldPath(fieldPath)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvvaluefromfieldrefwithfieldpath)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.resourceFieldRef`](#obj-specoverridestatefulsetspectemplatespeccontainersenvvaluefromresourcefieldref)
                    * [`fn withContainerName(containerName)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvvaluefromresourcefieldrefwithcontainername)
                    * [`fn withDivisor(divisor)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvvaluefromresourcefieldrefwithdivisor)
                    * [`fn withResource(resource)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvvaluefromresourcefieldrefwithresource)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.secretKeyRef`](#obj-specoverridestatefulsetspectemplatespeccontainersenvvaluefromsecretkeyref)
                    * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvvaluefromsecretkeyrefwithkey)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvvaluefromsecretkeyrefwithname)
                    * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvvaluefromsecretkeyrefwithoptional)
              * [`obj spec.override.statefulSet.spec.template.spec.containers.envFrom`](#obj-specoverridestatefulsetspectemplatespeccontainersenvfrom)
                * [`fn withPrefix(prefix)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvfromwithprefix)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.envFrom.configMapRef`](#obj-specoverridestatefulsetspectemplatespeccontainersenvfromconfigmapref)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvfromconfigmaprefwithname)
                  * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvfromconfigmaprefwithoptional)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.envFrom.secretRef`](#obj-specoverridestatefulsetspectemplatespeccontainersenvfromsecretref)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvfromsecretrefwithname)
                  * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespeccontainersenvfromsecretrefwithoptional)
              * [`obj spec.override.statefulSet.spec.template.spec.containers.lifecycle`](#obj-specoverridestatefulsetspectemplatespeccontainerslifecycle)
                * [`fn withStopSignal(stopSignal)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecyclewithstopsignal)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart`](#obj-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststart)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.exec`](#obj-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststartexec)
                    * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststartexecwithcommand)
                    * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststartexecwithcommandmixin)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.httpGet`](#obj-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststarthttpget)
                    * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststarthttpgetwithhost)
                    * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststarthttpgetwithhttpheaders)
                    * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststarthttpgetwithhttpheadersmixin)
                    * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststarthttpgetwithpath)
                    * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststarthttpgetwithport)
                    * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststarthttpgetwithscheme)
                    * [`obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststarthttpgethttpheaders)
                      * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststarthttpgethttpheaderswithname)
                      * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststarthttpgethttpheaderswithvalue)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.sleep`](#obj-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststartsleep)
                    * [`fn withSeconds(seconds)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststartsleepwithseconds)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.tcpSocket`](#obj-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststarttcpsocket)
                    * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststarttcpsocketwithhost)
                    * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecyclepoststarttcpsocketwithport)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop`](#obj-specoverridestatefulsetspectemplatespeccontainerslifecycleprestop)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.exec`](#obj-specoverridestatefulsetspectemplatespeccontainerslifecycleprestopexec)
                    * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecycleprestopexecwithcommand)
                    * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecycleprestopexecwithcommandmixin)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.httpGet`](#obj-specoverridestatefulsetspectemplatespeccontainerslifecycleprestophttpget)
                    * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecycleprestophttpgetwithhost)
                    * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecycleprestophttpgetwithhttpheaders)
                    * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecycleprestophttpgetwithhttpheadersmixin)
                    * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecycleprestophttpgetwithpath)
                    * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecycleprestophttpgetwithport)
                    * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecycleprestophttpgetwithscheme)
                    * [`obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespeccontainerslifecycleprestophttpgethttpheaders)
                      * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecycleprestophttpgethttpheaderswithname)
                      * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecycleprestophttpgethttpheaderswithvalue)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.sleep`](#obj-specoverridestatefulsetspectemplatespeccontainerslifecycleprestopsleep)
                    * [`fn withSeconds(seconds)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecycleprestopsleepwithseconds)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.tcpSocket`](#obj-specoverridestatefulsetspectemplatespeccontainerslifecycleprestoptcpsocket)
                    * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecycleprestoptcpsocketwithhost)
                    * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespeccontainerslifecycleprestoptcpsocketwithport)
              * [`obj spec.override.statefulSet.spec.template.spec.containers.livenessProbe`](#obj-specoverridestatefulsetspectemplatespeccontainerslivenessprobe)
                * [`fn withFailureThreshold(failureThreshold)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobewithfailurethreshold)
                * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobewithinitialdelayseconds)
                * [`fn withPeriodSeconds(periodSeconds)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobewithperiodseconds)
                * [`fn withSuccessThreshold(successThreshold)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobewithsuccessthreshold)
                * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobewithterminationgraceperiodseconds)
                * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobewithtimeoutseconds)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.livenessProbe.exec`](#obj-specoverridestatefulsetspectemplatespeccontainerslivenessprobeexec)
                  * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobeexecwithcommand)
                  * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobeexecwithcommandmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.livenessProbe.grpc`](#obj-specoverridestatefulsetspectemplatespeccontainerslivenessprobegrpc)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobegrpcwithport)
                  * [`fn withService(service)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobegrpcwithservice)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.livenessProbe.httpGet`](#obj-specoverridestatefulsetspectemplatespeccontainerslivenessprobehttpget)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobehttpgetwithhost)
                  * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobehttpgetwithhttpheaders)
                  * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobehttpgetwithhttpheadersmixin)
                  * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobehttpgetwithpath)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobehttpgetwithport)
                  * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobehttpgetwithscheme)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.livenessProbe.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespeccontainerslivenessprobehttpgethttpheaders)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobehttpgethttpheaderswithname)
                    * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobehttpgethttpheaderswithvalue)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.livenessProbe.tcpSocket`](#obj-specoverridestatefulsetspectemplatespeccontainerslivenessprobetcpsocket)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobetcpsocketwithhost)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespeccontainerslivenessprobetcpsocketwithport)
              * [`obj spec.override.statefulSet.spec.template.spec.containers.ports`](#obj-specoverridestatefulsetspectemplatespeccontainersports)
                * [`fn withContainerPort(containerPort)`](#fn-specoverridestatefulsetspectemplatespeccontainersportswithcontainerport)
                * [`fn withHostIP(hostIP)`](#fn-specoverridestatefulsetspectemplatespeccontainersportswithhostip)
                * [`fn withHostPort(hostPort)`](#fn-specoverridestatefulsetspectemplatespeccontainersportswithhostport)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainersportswithname)
                * [`fn withProtocol(protocol)`](#fn-specoverridestatefulsetspectemplatespeccontainersportswithprotocol)
              * [`obj spec.override.statefulSet.spec.template.spec.containers.readinessProbe`](#obj-specoverridestatefulsetspectemplatespeccontainersreadinessprobe)
                * [`fn withFailureThreshold(failureThreshold)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobewithfailurethreshold)
                * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobewithinitialdelayseconds)
                * [`fn withPeriodSeconds(periodSeconds)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobewithperiodseconds)
                * [`fn withSuccessThreshold(successThreshold)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobewithsuccessthreshold)
                * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobewithterminationgraceperiodseconds)
                * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobewithtimeoutseconds)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.readinessProbe.exec`](#obj-specoverridestatefulsetspectemplatespeccontainersreadinessprobeexec)
                  * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobeexecwithcommand)
                  * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobeexecwithcommandmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.readinessProbe.grpc`](#obj-specoverridestatefulsetspectemplatespeccontainersreadinessprobegrpc)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobegrpcwithport)
                  * [`fn withService(service)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobegrpcwithservice)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.readinessProbe.httpGet`](#obj-specoverridestatefulsetspectemplatespeccontainersreadinessprobehttpget)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobehttpgetwithhost)
                  * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobehttpgetwithhttpheaders)
                  * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobehttpgetwithhttpheadersmixin)
                  * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobehttpgetwithpath)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobehttpgetwithport)
                  * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobehttpgetwithscheme)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.readinessProbe.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespeccontainersreadinessprobehttpgethttpheaders)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobehttpgethttpheaderswithname)
                    * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobehttpgethttpheaderswithvalue)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.readinessProbe.tcpSocket`](#obj-specoverridestatefulsetspectemplatespeccontainersreadinessprobetcpsocket)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobetcpsocketwithhost)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespeccontainersreadinessprobetcpsocketwithport)
              * [`obj spec.override.statefulSet.spec.template.spec.containers.resizePolicy`](#obj-specoverridestatefulsetspectemplatespeccontainersresizepolicy)
                * [`fn withResourceName(resourceName)`](#fn-specoverridestatefulsetspectemplatespeccontainersresizepolicywithresourcename)
                * [`fn withRestartPolicy(restartPolicy)`](#fn-specoverridestatefulsetspectemplatespeccontainersresizepolicywithrestartpolicy)
              * [`obj spec.override.statefulSet.spec.template.spec.containers.resources`](#obj-specoverridestatefulsetspectemplatespeccontainersresources)
                * [`fn withClaims(claims)`](#fn-specoverridestatefulsetspectemplatespeccontainersresourceswithclaims)
                * [`fn withClaimsMixin(claims)`](#fn-specoverridestatefulsetspectemplatespeccontainersresourceswithclaimsmixin)
                * [`fn withLimits(limits)`](#fn-specoverridestatefulsetspectemplatespeccontainersresourceswithlimits)
                * [`fn withLimitsMixin(limits)`](#fn-specoverridestatefulsetspectemplatespeccontainersresourceswithlimitsmixin)
                * [`fn withRequests(requests)`](#fn-specoverridestatefulsetspectemplatespeccontainersresourceswithrequests)
                * [`fn withRequestsMixin(requests)`](#fn-specoverridestatefulsetspectemplatespeccontainersresourceswithrequestsmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.resources.claims`](#obj-specoverridestatefulsetspectemplatespeccontainersresourcesclaims)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainersresourcesclaimswithname)
                  * [`fn withRequest(request)`](#fn-specoverridestatefulsetspectemplatespeccontainersresourcesclaimswithrequest)
              * [`obj spec.override.statefulSet.spec.template.spec.containers.securityContext`](#obj-specoverridestatefulsetspectemplatespeccontainerssecuritycontext)
                * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextwithallowprivilegeescalation)
                * [`fn withPrivileged(privileged)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextwithprivileged)
                * [`fn withProcMount(procMount)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextwithprocmount)
                * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextwithreadonlyrootfilesystem)
                * [`fn withRunAsGroup(runAsGroup)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextwithrunasgroup)
                * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextwithrunasnonroot)
                * [`fn withRunAsUser(runAsUser)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextwithrunasuser)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.securityContext.appArmorProfile`](#obj-specoverridestatefulsetspectemplatespeccontainerssecuritycontextapparmorprofile)
                  * [`fn withLocalhostProfile(localhostProfile)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextapparmorprofilewithlocalhostprofile)
                  * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextapparmorprofilewithtype)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.securityContext.capabilities`](#obj-specoverridestatefulsetspectemplatespeccontainerssecuritycontextcapabilities)
                  * [`fn withAdd(add)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextcapabilitieswithadd)
                  * [`fn withAddMixin(add)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextcapabilitieswithaddmixin)
                  * [`fn withDrop(drop)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextcapabilitieswithdrop)
                  * [`fn withDropMixin(drop)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextcapabilitieswithdropmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.securityContext.seLinuxOptions`](#obj-specoverridestatefulsetspectemplatespeccontainerssecuritycontextselinuxoptions)
                  * [`fn withLevel(level)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextselinuxoptionswithlevel)
                  * [`fn withRole(role)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextselinuxoptionswithrole)
                  * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextselinuxoptionswithtype)
                  * [`fn withUser(user)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextselinuxoptionswithuser)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.securityContext.seccompProfile`](#obj-specoverridestatefulsetspectemplatespeccontainerssecuritycontextseccompprofile)
                  * [`fn withLocalhostProfile(localhostProfile)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextseccompprofilewithlocalhostprofile)
                  * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextseccompprofilewithtype)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.securityContext.windowsOptions`](#obj-specoverridestatefulsetspectemplatespeccontainerssecuritycontextwindowsoptions)
                  * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextwindowsoptionswithgmsacredentialspec)
                  * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextwindowsoptionswithgmsacredentialspecname)
                  * [`fn withHostProcess(hostProcess)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextwindowsoptionswithhostprocess)
                  * [`fn withRunAsUserName(runAsUserName)`](#fn-specoverridestatefulsetspectemplatespeccontainerssecuritycontextwindowsoptionswithrunasusername)
              * [`obj spec.override.statefulSet.spec.template.spec.containers.startupProbe`](#obj-specoverridestatefulsetspectemplatespeccontainersstartupprobe)
                * [`fn withFailureThreshold(failureThreshold)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobewithfailurethreshold)
                * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobewithinitialdelayseconds)
                * [`fn withPeriodSeconds(periodSeconds)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobewithperiodseconds)
                * [`fn withSuccessThreshold(successThreshold)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobewithsuccessthreshold)
                * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobewithterminationgraceperiodseconds)
                * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobewithtimeoutseconds)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.startupProbe.exec`](#obj-specoverridestatefulsetspectemplatespeccontainersstartupprobeexec)
                  * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobeexecwithcommand)
                  * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobeexecwithcommandmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.startupProbe.grpc`](#obj-specoverridestatefulsetspectemplatespeccontainersstartupprobegrpc)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobegrpcwithport)
                  * [`fn withService(service)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobegrpcwithservice)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.startupProbe.httpGet`](#obj-specoverridestatefulsetspectemplatespeccontainersstartupprobehttpget)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobehttpgetwithhost)
                  * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobehttpgetwithhttpheaders)
                  * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobehttpgetwithhttpheadersmixin)
                  * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobehttpgetwithpath)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobehttpgetwithport)
                  * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobehttpgetwithscheme)
                  * [`obj spec.override.statefulSet.spec.template.spec.containers.startupProbe.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespeccontainersstartupprobehttpgethttpheaders)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobehttpgethttpheaderswithname)
                    * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobehttpgethttpheaderswithvalue)
                * [`obj spec.override.statefulSet.spec.template.spec.containers.startupProbe.tcpSocket`](#obj-specoverridestatefulsetspectemplatespeccontainersstartupprobetcpsocket)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobetcpsocketwithhost)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespeccontainersstartupprobetcpsocketwithport)
              * [`obj spec.override.statefulSet.spec.template.spec.containers.volumeDevices`](#obj-specoverridestatefulsetspectemplatespeccontainersvolumedevices)
                * [`fn withDevicePath(devicePath)`](#fn-specoverridestatefulsetspectemplatespeccontainersvolumedeviceswithdevicepath)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainersvolumedeviceswithname)
              * [`obj spec.override.statefulSet.spec.template.spec.containers.volumeMounts`](#obj-specoverridestatefulsetspectemplatespeccontainersvolumemounts)
                * [`fn withMountPath(mountPath)`](#fn-specoverridestatefulsetspectemplatespeccontainersvolumemountswithmountpath)
                * [`fn withMountPropagation(mountPropagation)`](#fn-specoverridestatefulsetspectemplatespeccontainersvolumemountswithmountpropagation)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespeccontainersvolumemountswithname)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespeccontainersvolumemountswithreadonly)
                * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specoverridestatefulsetspectemplatespeccontainersvolumemountswithrecursivereadonly)
                * [`fn withSubPath(subPath)`](#fn-specoverridestatefulsetspectemplatespeccontainersvolumemountswithsubpath)
                * [`fn withSubPathExpr(subPathExpr)`](#fn-specoverridestatefulsetspectemplatespeccontainersvolumemountswithsubpathexpr)
            * [`obj spec.override.statefulSet.spec.template.spec.dnsConfig`](#obj-specoverridestatefulsetspectemplatespecdnsconfig)
              * [`fn withNameservers(nameservers)`](#fn-specoverridestatefulsetspectemplatespecdnsconfigwithnameservers)
              * [`fn withNameserversMixin(nameservers)`](#fn-specoverridestatefulsetspectemplatespecdnsconfigwithnameserversmixin)
              * [`fn withOptions(options)`](#fn-specoverridestatefulsetspectemplatespecdnsconfigwithoptions)
              * [`fn withOptionsMixin(options)`](#fn-specoverridestatefulsetspectemplatespecdnsconfigwithoptionsmixin)
              * [`fn withSearches(searches)`](#fn-specoverridestatefulsetspectemplatespecdnsconfigwithsearches)
              * [`fn withSearchesMixin(searches)`](#fn-specoverridestatefulsetspectemplatespecdnsconfigwithsearchesmixin)
              * [`obj spec.override.statefulSet.spec.template.spec.dnsConfig.options`](#obj-specoverridestatefulsetspectemplatespecdnsconfigoptions)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecdnsconfigoptionswithname)
                * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespecdnsconfigoptionswithvalue)
            * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainers)
              * [`fn withArgs(args)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithargs)
              * [`fn withArgsMixin(args)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithargsmixin)
              * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithcommand)
              * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithcommandmixin)
              * [`fn withEnv(env)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithenv)
              * [`fn withEnvFrom(envFrom)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithenvfrom)
              * [`fn withEnvFromMixin(envFrom)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithenvfrommixin)
              * [`fn withEnvMixin(env)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithenvmixin)
              * [`fn withImage(image)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithimage)
              * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithimagepullpolicy)
              * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithname)
              * [`fn withPorts(ports)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithports)
              * [`fn withPortsMixin(ports)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithportsmixin)
              * [`fn withResizePolicy(resizePolicy)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithresizepolicy)
              * [`fn withResizePolicyMixin(resizePolicy)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithresizepolicymixin)
              * [`fn withRestartPolicy(restartPolicy)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithrestartpolicy)
              * [`fn withStdin(stdin)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithstdin)
              * [`fn withStdinOnce(stdinOnce)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithstdinonce)
              * [`fn withTargetContainerName(targetContainerName)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithtargetcontainername)
              * [`fn withTerminationMessagePath(terminationMessagePath)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithterminationmessagepath)
              * [`fn withTerminationMessagePolicy(terminationMessagePolicy)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithterminationmessagepolicy)
              * [`fn withTty(tty)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithtty)
              * [`fn withVolumeDevices(volumeDevices)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithvolumedevices)
              * [`fn withVolumeDevicesMixin(volumeDevices)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithvolumedevicesmixin)
              * [`fn withVolumeMounts(volumeMounts)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithvolumemounts)
              * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithvolumemountsmixin)
              * [`fn withWorkingDir(workingDir)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerswithworkingdir)
              * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.env`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersenv)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvwithname)
                * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvwithvalue)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefrom)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.configMapKeyRef`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromconfigmapkeyref)
                    * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromconfigmapkeyrefwithkey)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromconfigmapkeyrefwithname)
                    * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromconfigmapkeyrefwithoptional)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.fieldRef`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromfieldref)
                    * [`fn withApiVersion(apiVersion)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromfieldrefwithapiversion)
                    * [`fn withFieldPath(fieldPath)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromfieldrefwithfieldpath)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.resourceFieldRef`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromresourcefieldref)
                    * [`fn withContainerName(containerName)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromresourcefieldrefwithcontainername)
                    * [`fn withDivisor(divisor)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromresourcefieldrefwithdivisor)
                    * [`fn withResource(resource)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromresourcefieldrefwithresource)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.secretKeyRef`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromsecretkeyref)
                    * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromsecretkeyrefwithkey)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromsecretkeyrefwithname)
                    * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvvaluefromsecretkeyrefwithoptional)
              * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.envFrom`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersenvfrom)
                * [`fn withPrefix(prefix)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvfromwithprefix)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.envFrom.configMapRef`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersenvfromconfigmapref)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvfromconfigmaprefwithname)
                  * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvfromconfigmaprefwithoptional)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.envFrom.secretRef`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersenvfromsecretref)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvfromsecretrefwithname)
                  * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersenvfromsecretrefwithoptional)
              * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycle)
                * [`fn withStopSignal(stopSignal)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclewithstopsignal)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststart)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.exec`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststartexec)
                    * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststartexecwithcommand)
                    * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststartexecwithcommandmixin)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.httpGet`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststarthttpget)
                    * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststarthttpgetwithhost)
                    * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststarthttpgetwithhttpheaders)
                    * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststarthttpgetwithhttpheadersmixin)
                    * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststarthttpgetwithpath)
                    * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststarthttpgetwithport)
                    * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststarthttpgetwithscheme)
                    * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststarthttpgethttpheaders)
                      * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststarthttpgethttpheaderswithname)
                      * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststarthttpgethttpheaderswithvalue)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.sleep`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststartsleep)
                    * [`fn withSeconds(seconds)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststartsleepwithseconds)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.tcpSocket`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststarttcpsocket)
                    * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststarttcpsocketwithhost)
                    * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecyclepoststarttcpsocketwithport)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestop)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.exec`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestopexec)
                    * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestopexecwithcommand)
                    * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestopexecwithcommandmixin)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.httpGet`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestophttpget)
                    * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestophttpgetwithhost)
                    * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestophttpgetwithhttpheaders)
                    * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestophttpgetwithhttpheadersmixin)
                    * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestophttpgetwithpath)
                    * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestophttpgetwithport)
                    * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestophttpgetwithscheme)
                    * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestophttpgethttpheaders)
                      * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestophttpgethttpheaderswithname)
                      * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestophttpgethttpheaderswithvalue)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.sleep`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestopsleep)
                    * [`fn withSeconds(seconds)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestopsleepwithseconds)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.tcpSocket`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestoptcpsocket)
                    * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestoptcpsocketwithhost)
                    * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslifecycleprestoptcpsocketwithport)
              * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobe)
                * [`fn withFailureThreshold(failureThreshold)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobewithfailurethreshold)
                * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobewithinitialdelayseconds)
                * [`fn withPeriodSeconds(periodSeconds)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobewithperiodseconds)
                * [`fn withSuccessThreshold(successThreshold)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobewithsuccessthreshold)
                * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobewithterminationgraceperiodseconds)
                * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobewithtimeoutseconds)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.exec`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobeexec)
                  * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobeexecwithcommand)
                  * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobeexecwithcommandmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.grpc`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobegrpc)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobegrpcwithport)
                  * [`fn withService(service)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobegrpcwithservice)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.httpGet`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobehttpget)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobehttpgetwithhost)
                  * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobehttpgetwithhttpheaders)
                  * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobehttpgetwithhttpheadersmixin)
                  * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobehttpgetwithpath)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobehttpgetwithport)
                  * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobehttpgetwithscheme)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobehttpgethttpheaders)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobehttpgethttpheaderswithname)
                    * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobehttpgethttpheaderswithvalue)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.tcpSocket`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobetcpsocket)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobetcpsocketwithhost)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerslivenessprobetcpsocketwithport)
              * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.ports`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersports)
                * [`fn withContainerPort(containerPort)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersportswithcontainerport)
                * [`fn withHostIP(hostIP)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersportswithhostip)
                * [`fn withHostPort(hostPort)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersportswithhostport)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersportswithname)
                * [`fn withProtocol(protocol)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersportswithprotocol)
              * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobe)
                * [`fn withFailureThreshold(failureThreshold)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobewithfailurethreshold)
                * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobewithinitialdelayseconds)
                * [`fn withPeriodSeconds(periodSeconds)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobewithperiodseconds)
                * [`fn withSuccessThreshold(successThreshold)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobewithsuccessthreshold)
                * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobewithterminationgraceperiodseconds)
                * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobewithtimeoutseconds)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.exec`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobeexec)
                  * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobeexecwithcommand)
                  * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobeexecwithcommandmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.grpc`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobegrpc)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobegrpcwithport)
                  * [`fn withService(service)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobegrpcwithservice)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.httpGet`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobehttpget)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobehttpgetwithhost)
                  * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobehttpgetwithhttpheaders)
                  * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobehttpgetwithhttpheadersmixin)
                  * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobehttpgetwithpath)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobehttpgetwithport)
                  * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobehttpgetwithscheme)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobehttpgethttpheaders)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobehttpgethttpheaderswithname)
                    * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobehttpgethttpheaderswithvalue)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.tcpSocket`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobetcpsocket)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobetcpsocketwithhost)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersreadinessprobetcpsocketwithport)
              * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.resizePolicy`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersresizepolicy)
                * [`fn withResourceName(resourceName)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersresizepolicywithresourcename)
                * [`fn withRestartPolicy(restartPolicy)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersresizepolicywithrestartpolicy)
              * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.resources`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersresources)
                * [`fn withClaims(claims)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersresourceswithclaims)
                * [`fn withClaimsMixin(claims)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersresourceswithclaimsmixin)
                * [`fn withLimits(limits)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersresourceswithlimits)
                * [`fn withLimitsMixin(limits)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersresourceswithlimitsmixin)
                * [`fn withRequests(requests)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersresourceswithrequests)
                * [`fn withRequestsMixin(requests)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersresourceswithrequestsmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.resources.claims`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersresourcesclaims)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersresourcesclaimswithname)
                  * [`fn withRequest(request)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersresourcesclaimswithrequest)
              * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontext)
                * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextwithallowprivilegeescalation)
                * [`fn withPrivileged(privileged)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextwithprivileged)
                * [`fn withProcMount(procMount)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextwithprocmount)
                * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextwithreadonlyrootfilesystem)
                * [`fn withRunAsGroup(runAsGroup)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextwithrunasgroup)
                * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextwithrunasnonroot)
                * [`fn withRunAsUser(runAsUser)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextwithrunasuser)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.appArmorProfile`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextapparmorprofile)
                  * [`fn withLocalhostProfile(localhostProfile)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextapparmorprofilewithlocalhostprofile)
                  * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextapparmorprofilewithtype)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.capabilities`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextcapabilities)
                  * [`fn withAdd(add)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextcapabilitieswithadd)
                  * [`fn withAddMixin(add)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextcapabilitieswithaddmixin)
                  * [`fn withDrop(drop)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextcapabilitieswithdrop)
                  * [`fn withDropMixin(drop)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextcapabilitieswithdropmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.seLinuxOptions`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextselinuxoptions)
                  * [`fn withLevel(level)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextselinuxoptionswithlevel)
                  * [`fn withRole(role)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextselinuxoptionswithrole)
                  * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextselinuxoptionswithtype)
                  * [`fn withUser(user)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextselinuxoptionswithuser)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.seccompProfile`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextseccompprofile)
                  * [`fn withLocalhostProfile(localhostProfile)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextseccompprofilewithlocalhostprofile)
                  * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextseccompprofilewithtype)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.windowsOptions`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextwindowsoptions)
                  * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextwindowsoptionswithgmsacredentialspec)
                  * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextwindowsoptionswithgmsacredentialspecname)
                  * [`fn withHostProcess(hostProcess)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextwindowsoptionswithhostprocess)
                  * [`fn withRunAsUserName(runAsUserName)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainerssecuritycontextwindowsoptionswithrunasusername)
              * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobe)
                * [`fn withFailureThreshold(failureThreshold)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobewithfailurethreshold)
                * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobewithinitialdelayseconds)
                * [`fn withPeriodSeconds(periodSeconds)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobewithperiodseconds)
                * [`fn withSuccessThreshold(successThreshold)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobewithsuccessthreshold)
                * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobewithterminationgraceperiodseconds)
                * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobewithtimeoutseconds)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.exec`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobeexec)
                  * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobeexecwithcommand)
                  * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobeexecwithcommandmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.grpc`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobegrpc)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobegrpcwithport)
                  * [`fn withService(service)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobegrpcwithservice)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.httpGet`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobehttpget)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobehttpgetwithhost)
                  * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobehttpgetwithhttpheaders)
                  * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobehttpgetwithhttpheadersmixin)
                  * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobehttpgetwithpath)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobehttpgetwithport)
                  * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobehttpgetwithscheme)
                  * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobehttpgethttpheaders)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobehttpgethttpheaderswithname)
                    * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobehttpgethttpheaderswithvalue)
                * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.tcpSocket`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobetcpsocket)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobetcpsocketwithhost)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersstartupprobetcpsocketwithport)
              * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.volumeDevices`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersvolumedevices)
                * [`fn withDevicePath(devicePath)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersvolumedeviceswithdevicepath)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersvolumedeviceswithname)
              * [`obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.volumeMounts`](#obj-specoverridestatefulsetspectemplatespecephemeralcontainersvolumemounts)
                * [`fn withMountPath(mountPath)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersvolumemountswithmountpath)
                * [`fn withMountPropagation(mountPropagation)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersvolumemountswithmountpropagation)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersvolumemountswithname)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersvolumemountswithreadonly)
                * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersvolumemountswithrecursivereadonly)
                * [`fn withSubPath(subPath)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersvolumemountswithsubpath)
                * [`fn withSubPathExpr(subPathExpr)`](#fn-specoverridestatefulsetspectemplatespecephemeralcontainersvolumemountswithsubpathexpr)
            * [`obj spec.override.statefulSet.spec.template.spec.hostAliases`](#obj-specoverridestatefulsetspectemplatespechostaliases)
              * [`fn withHostnames(hostnames)`](#fn-specoverridestatefulsetspectemplatespechostaliaseswithhostnames)
              * [`fn withHostnamesMixin(hostnames)`](#fn-specoverridestatefulsetspectemplatespechostaliaseswithhostnamesmixin)
              * [`fn withIp(ip)`](#fn-specoverridestatefulsetspectemplatespechostaliaseswithip)
            * [`obj spec.override.statefulSet.spec.template.spec.imagePullSecrets`](#obj-specoverridestatefulsetspectemplatespecimagepullsecrets)
              * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecimagepullsecretswithname)
            * [`obj spec.override.statefulSet.spec.template.spec.initContainers`](#obj-specoverridestatefulsetspectemplatespecinitcontainers)
              * [`fn withArgs(args)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithargs)
              * [`fn withArgsMixin(args)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithargsmixin)
              * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithcommand)
              * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithcommandmixin)
              * [`fn withEnv(env)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithenv)
              * [`fn withEnvFrom(envFrom)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithenvfrom)
              * [`fn withEnvFromMixin(envFrom)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithenvfrommixin)
              * [`fn withEnvMixin(env)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithenvmixin)
              * [`fn withImage(image)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithimage)
              * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithimagepullpolicy)
              * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithname)
              * [`fn withPorts(ports)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithports)
              * [`fn withPortsMixin(ports)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithportsmixin)
              * [`fn withResizePolicy(resizePolicy)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithresizepolicy)
              * [`fn withResizePolicyMixin(resizePolicy)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithresizepolicymixin)
              * [`fn withRestartPolicy(restartPolicy)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithrestartpolicy)
              * [`fn withStdin(stdin)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithstdin)
              * [`fn withStdinOnce(stdinOnce)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithstdinonce)
              * [`fn withTerminationMessagePath(terminationMessagePath)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithterminationmessagepath)
              * [`fn withTerminationMessagePolicy(terminationMessagePolicy)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithterminationmessagepolicy)
              * [`fn withTty(tty)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithtty)
              * [`fn withVolumeDevices(volumeDevices)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithvolumedevices)
              * [`fn withVolumeDevicesMixin(volumeDevices)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithvolumedevicesmixin)
              * [`fn withVolumeMounts(volumeMounts)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithvolumemounts)
              * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithvolumemountsmixin)
              * [`fn withWorkingDir(workingDir)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerswithworkingdir)
              * [`obj spec.override.statefulSet.spec.template.spec.initContainers.env`](#obj-specoverridestatefulsetspectemplatespecinitcontainersenv)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvwithname)
                * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvwithvalue)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom`](#obj-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefrom)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.configMapKeyRef`](#obj-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromconfigmapkeyref)
                    * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromconfigmapkeyrefwithkey)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromconfigmapkeyrefwithname)
                    * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromconfigmapkeyrefwithoptional)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.fieldRef`](#obj-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromfieldref)
                    * [`fn withApiVersion(apiVersion)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromfieldrefwithapiversion)
                    * [`fn withFieldPath(fieldPath)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromfieldrefwithfieldpath)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.resourceFieldRef`](#obj-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromresourcefieldref)
                    * [`fn withContainerName(containerName)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromresourcefieldrefwithcontainername)
                    * [`fn withDivisor(divisor)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromresourcefieldrefwithdivisor)
                    * [`fn withResource(resource)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromresourcefieldrefwithresource)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.secretKeyRef`](#obj-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromsecretkeyref)
                    * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromsecretkeyrefwithkey)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromsecretkeyrefwithname)
                    * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvvaluefromsecretkeyrefwithoptional)
              * [`obj spec.override.statefulSet.spec.template.spec.initContainers.envFrom`](#obj-specoverridestatefulsetspectemplatespecinitcontainersenvfrom)
                * [`fn withPrefix(prefix)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvfromwithprefix)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.envFrom.configMapRef`](#obj-specoverridestatefulsetspectemplatespecinitcontainersenvfromconfigmapref)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvfromconfigmaprefwithname)
                  * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvfromconfigmaprefwithoptional)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.envFrom.secretRef`](#obj-specoverridestatefulsetspectemplatespecinitcontainersenvfromsecretref)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvfromsecretrefwithname)
                  * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersenvfromsecretrefwithoptional)
              * [`obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslifecycle)
                * [`fn withStopSignal(stopSignal)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecyclewithstopsignal)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststart)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.exec`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststartexec)
                    * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststartexecwithcommand)
                    * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststartexecwithcommandmixin)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.httpGet`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststarthttpget)
                    * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststarthttpgetwithhost)
                    * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststarthttpgetwithhttpheaders)
                    * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststarthttpgetwithhttpheadersmixin)
                    * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststarthttpgetwithpath)
                    * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststarthttpgetwithport)
                    * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststarthttpgetwithscheme)
                    * [`obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststarthttpgethttpheaders)
                      * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststarthttpgethttpheaderswithname)
                      * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststarthttpgethttpheaderswithvalue)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.sleep`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststartsleep)
                    * [`fn withSeconds(seconds)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststartsleepwithseconds)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.tcpSocket`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststarttcpsocket)
                    * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststarttcpsocketwithhost)
                    * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecyclepoststarttcpsocketwithport)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestop)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.exec`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestopexec)
                    * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestopexecwithcommand)
                    * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestopexecwithcommandmixin)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.httpGet`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestophttpget)
                    * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestophttpgetwithhost)
                    * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestophttpgetwithhttpheaders)
                    * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestophttpgetwithhttpheadersmixin)
                    * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestophttpgetwithpath)
                    * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestophttpgetwithport)
                    * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestophttpgetwithscheme)
                    * [`obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestophttpgethttpheaders)
                      * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestophttpgethttpheaderswithname)
                      * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestophttpgethttpheaderswithvalue)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.sleep`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestopsleep)
                    * [`fn withSeconds(seconds)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestopsleepwithseconds)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.tcpSocket`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestoptcpsocket)
                    * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestoptcpsocketwithhost)
                    * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslifecycleprestoptcpsocketwithport)
              * [`obj spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobe)
                * [`fn withFailureThreshold(failureThreshold)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobewithfailurethreshold)
                * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobewithinitialdelayseconds)
                * [`fn withPeriodSeconds(periodSeconds)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobewithperiodseconds)
                * [`fn withSuccessThreshold(successThreshold)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobewithsuccessthreshold)
                * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobewithterminationgraceperiodseconds)
                * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobewithtimeoutseconds)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.exec`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobeexec)
                  * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobeexecwithcommand)
                  * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobeexecwithcommandmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.grpc`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobegrpc)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobegrpcwithport)
                  * [`fn withService(service)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobegrpcwithservice)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.httpGet`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobehttpget)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobehttpgetwithhost)
                  * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobehttpgetwithhttpheaders)
                  * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobehttpgetwithhttpheadersmixin)
                  * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobehttpgetwithpath)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobehttpgetwithport)
                  * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobehttpgetwithscheme)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobehttpgethttpheaders)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobehttpgethttpheaderswithname)
                    * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobehttpgethttpheaderswithvalue)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.tcpSocket`](#obj-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobetcpsocket)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobetcpsocketwithhost)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerslivenessprobetcpsocketwithport)
              * [`obj spec.override.statefulSet.spec.template.spec.initContainers.ports`](#obj-specoverridestatefulsetspectemplatespecinitcontainersports)
                * [`fn withContainerPort(containerPort)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersportswithcontainerport)
                * [`fn withHostIP(hostIP)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersportswithhostip)
                * [`fn withHostPort(hostPort)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersportswithhostport)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersportswithname)
                * [`fn withProtocol(protocol)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersportswithprotocol)
              * [`obj spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe`](#obj-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobe)
                * [`fn withFailureThreshold(failureThreshold)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobewithfailurethreshold)
                * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobewithinitialdelayseconds)
                * [`fn withPeriodSeconds(periodSeconds)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobewithperiodseconds)
                * [`fn withSuccessThreshold(successThreshold)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobewithsuccessthreshold)
                * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobewithterminationgraceperiodseconds)
                * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobewithtimeoutseconds)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.exec`](#obj-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobeexec)
                  * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobeexecwithcommand)
                  * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobeexecwithcommandmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.grpc`](#obj-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobegrpc)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobegrpcwithport)
                  * [`fn withService(service)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobegrpcwithservice)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.httpGet`](#obj-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobehttpget)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobehttpgetwithhost)
                  * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobehttpgetwithhttpheaders)
                  * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobehttpgetwithhttpheadersmixin)
                  * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobehttpgetwithpath)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobehttpgetwithport)
                  * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobehttpgetwithscheme)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobehttpgethttpheaders)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobehttpgethttpheaderswithname)
                    * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobehttpgethttpheaderswithvalue)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.tcpSocket`](#obj-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobetcpsocket)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobetcpsocketwithhost)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersreadinessprobetcpsocketwithport)
              * [`obj spec.override.statefulSet.spec.template.spec.initContainers.resizePolicy`](#obj-specoverridestatefulsetspectemplatespecinitcontainersresizepolicy)
                * [`fn withResourceName(resourceName)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersresizepolicywithresourcename)
                * [`fn withRestartPolicy(restartPolicy)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersresizepolicywithrestartpolicy)
              * [`obj spec.override.statefulSet.spec.template.spec.initContainers.resources`](#obj-specoverridestatefulsetspectemplatespecinitcontainersresources)
                * [`fn withClaims(claims)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersresourceswithclaims)
                * [`fn withClaimsMixin(claims)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersresourceswithclaimsmixin)
                * [`fn withLimits(limits)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersresourceswithlimits)
                * [`fn withLimitsMixin(limits)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersresourceswithlimitsmixin)
                * [`fn withRequests(requests)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersresourceswithrequests)
                * [`fn withRequestsMixin(requests)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersresourceswithrequestsmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.resources.claims`](#obj-specoverridestatefulsetspectemplatespecinitcontainersresourcesclaims)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersresourcesclaimswithname)
                  * [`fn withRequest(request)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersresourcesclaimswithrequest)
              * [`obj spec.override.statefulSet.spec.template.spec.initContainers.securityContext`](#obj-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontext)
                * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextwithallowprivilegeescalation)
                * [`fn withPrivileged(privileged)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextwithprivileged)
                * [`fn withProcMount(procMount)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextwithprocmount)
                * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextwithreadonlyrootfilesystem)
                * [`fn withRunAsGroup(runAsGroup)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextwithrunasgroup)
                * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextwithrunasnonroot)
                * [`fn withRunAsUser(runAsUser)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextwithrunasuser)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.securityContext.appArmorProfile`](#obj-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextapparmorprofile)
                  * [`fn withLocalhostProfile(localhostProfile)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextapparmorprofilewithlocalhostprofile)
                  * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextapparmorprofilewithtype)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.securityContext.capabilities`](#obj-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextcapabilities)
                  * [`fn withAdd(add)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextcapabilitieswithadd)
                  * [`fn withAddMixin(add)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextcapabilitieswithaddmixin)
                  * [`fn withDrop(drop)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextcapabilitieswithdrop)
                  * [`fn withDropMixin(drop)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextcapabilitieswithdropmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.securityContext.seLinuxOptions`](#obj-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextselinuxoptions)
                  * [`fn withLevel(level)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextselinuxoptionswithlevel)
                  * [`fn withRole(role)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextselinuxoptionswithrole)
                  * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextselinuxoptionswithtype)
                  * [`fn withUser(user)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextselinuxoptionswithuser)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.securityContext.seccompProfile`](#obj-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextseccompprofile)
                  * [`fn withLocalhostProfile(localhostProfile)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextseccompprofilewithlocalhostprofile)
                  * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextseccompprofilewithtype)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.securityContext.windowsOptions`](#obj-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextwindowsoptions)
                  * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextwindowsoptionswithgmsacredentialspec)
                  * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextwindowsoptionswithgmsacredentialspecname)
                  * [`fn withHostProcess(hostProcess)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextwindowsoptionswithhostprocess)
                  * [`fn withRunAsUserName(runAsUserName)`](#fn-specoverridestatefulsetspectemplatespecinitcontainerssecuritycontextwindowsoptionswithrunasusername)
              * [`obj spec.override.statefulSet.spec.template.spec.initContainers.startupProbe`](#obj-specoverridestatefulsetspectemplatespecinitcontainersstartupprobe)
                * [`fn withFailureThreshold(failureThreshold)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobewithfailurethreshold)
                * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobewithinitialdelayseconds)
                * [`fn withPeriodSeconds(periodSeconds)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobewithperiodseconds)
                * [`fn withSuccessThreshold(successThreshold)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobewithsuccessthreshold)
                * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobewithterminationgraceperiodseconds)
                * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobewithtimeoutseconds)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.exec`](#obj-specoverridestatefulsetspectemplatespecinitcontainersstartupprobeexec)
                  * [`fn withCommand(command)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobeexecwithcommand)
                  * [`fn withCommandMixin(command)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobeexecwithcommandmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.grpc`](#obj-specoverridestatefulsetspectemplatespecinitcontainersstartupprobegrpc)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobegrpcwithport)
                  * [`fn withService(service)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobegrpcwithservice)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.httpGet`](#obj-specoverridestatefulsetspectemplatespecinitcontainersstartupprobehttpget)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobehttpgetwithhost)
                  * [`fn withHttpHeaders(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobehttpgetwithhttpheaders)
                  * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobehttpgetwithhttpheadersmixin)
                  * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobehttpgetwithpath)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobehttpgetwithport)
                  * [`fn withScheme(scheme)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobehttpgetwithscheme)
                  * [`obj spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.httpGet.httpHeaders`](#obj-specoverridestatefulsetspectemplatespecinitcontainersstartupprobehttpgethttpheaders)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobehttpgethttpheaderswithname)
                    * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobehttpgethttpheaderswithvalue)
                * [`obj spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.tcpSocket`](#obj-specoverridestatefulsetspectemplatespecinitcontainersstartupprobetcpsocket)
                  * [`fn withHost(host)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobetcpsocketwithhost)
                  * [`fn withPort(port)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersstartupprobetcpsocketwithport)
              * [`obj spec.override.statefulSet.spec.template.spec.initContainers.volumeDevices`](#obj-specoverridestatefulsetspectemplatespecinitcontainersvolumedevices)
                * [`fn withDevicePath(devicePath)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersvolumedeviceswithdevicepath)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersvolumedeviceswithname)
              * [`obj spec.override.statefulSet.spec.template.spec.initContainers.volumeMounts`](#obj-specoverridestatefulsetspectemplatespecinitcontainersvolumemounts)
                * [`fn withMountPath(mountPath)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersvolumemountswithmountpath)
                * [`fn withMountPropagation(mountPropagation)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersvolumemountswithmountpropagation)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersvolumemountswithname)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersvolumemountswithreadonly)
                * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersvolumemountswithrecursivereadonly)
                * [`fn withSubPath(subPath)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersvolumemountswithsubpath)
                * [`fn withSubPathExpr(subPathExpr)`](#fn-specoverridestatefulsetspectemplatespecinitcontainersvolumemountswithsubpathexpr)
            * [`obj spec.override.statefulSet.spec.template.spec.os`](#obj-specoverridestatefulsetspectemplatespecos)
              * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecoswithname)
            * [`obj spec.override.statefulSet.spec.template.spec.readinessGates`](#obj-specoverridestatefulsetspectemplatespecreadinessgates)
              * [`fn withConditionType(conditionType)`](#fn-specoverridestatefulsetspectemplatespecreadinessgateswithconditiontype)
            * [`obj spec.override.statefulSet.spec.template.spec.resourceClaims`](#obj-specoverridestatefulsetspectemplatespecresourceclaims)
              * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecresourceclaimswithname)
              * [`fn withResourceClaimName(resourceClaimName)`](#fn-specoverridestatefulsetspectemplatespecresourceclaimswithresourceclaimname)
              * [`fn withResourceClaimTemplateName(resourceClaimTemplateName)`](#fn-specoverridestatefulsetspectemplatespecresourceclaimswithresourceclaimtemplatename)
            * [`obj spec.override.statefulSet.spec.template.spec.resources`](#obj-specoverridestatefulsetspectemplatespecresources)
              * [`fn withClaims(claims)`](#fn-specoverridestatefulsetspectemplatespecresourceswithclaims)
              * [`fn withClaimsMixin(claims)`](#fn-specoverridestatefulsetspectemplatespecresourceswithclaimsmixin)
              * [`fn withLimits(limits)`](#fn-specoverridestatefulsetspectemplatespecresourceswithlimits)
              * [`fn withLimitsMixin(limits)`](#fn-specoverridestatefulsetspectemplatespecresourceswithlimitsmixin)
              * [`fn withRequests(requests)`](#fn-specoverridestatefulsetspectemplatespecresourceswithrequests)
              * [`fn withRequestsMixin(requests)`](#fn-specoverridestatefulsetspectemplatespecresourceswithrequestsmixin)
              * [`obj spec.override.statefulSet.spec.template.spec.resources.claims`](#obj-specoverridestatefulsetspectemplatespecresourcesclaims)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecresourcesclaimswithname)
                * [`fn withRequest(request)`](#fn-specoverridestatefulsetspectemplatespecresourcesclaimswithrequest)
            * [`obj spec.override.statefulSet.spec.template.spec.schedulingGates`](#obj-specoverridestatefulsetspectemplatespecschedulinggates)
              * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecschedulinggateswithname)
            * [`obj spec.override.statefulSet.spec.template.spec.securityContext`](#obj-specoverridestatefulsetspectemplatespecsecuritycontext)
              * [`fn withFsGroup(fsGroup)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithfsgroup)
              * [`fn withFsGroupChangePolicy(fsGroupChangePolicy)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithfsgroupchangepolicy)
              * [`fn withRunAsGroup(runAsGroup)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithrunasgroup)
              * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithrunasnonroot)
              * [`fn withRunAsUser(runAsUser)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithrunasuser)
              * [`fn withSeLinuxChangePolicy(seLinuxChangePolicy)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithselinuxchangepolicy)
              * [`fn withSupplementalGroups(supplementalGroups)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithsupplementalgroups)
              * [`fn withSupplementalGroupsMixin(supplementalGroups)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithsupplementalgroupsmixin)
              * [`fn withSupplementalGroupsPolicy(supplementalGroupsPolicy)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithsupplementalgroupspolicy)
              * [`fn withSysctls(sysctls)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithsysctls)
              * [`fn withSysctlsMixin(sysctls)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwithsysctlsmixin)
              * [`obj spec.override.statefulSet.spec.template.spec.securityContext.appArmorProfile`](#obj-specoverridestatefulsetspectemplatespecsecuritycontextapparmorprofile)
                * [`fn withLocalhostProfile(localhostProfile)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextapparmorprofilewithlocalhostprofile)
                * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextapparmorprofilewithtype)
              * [`obj spec.override.statefulSet.spec.template.spec.securityContext.seLinuxOptions`](#obj-specoverridestatefulsetspectemplatespecsecuritycontextselinuxoptions)
                * [`fn withLevel(level)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextselinuxoptionswithlevel)
                * [`fn withRole(role)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextselinuxoptionswithrole)
                * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextselinuxoptionswithtype)
                * [`fn withUser(user)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextselinuxoptionswithuser)
              * [`obj spec.override.statefulSet.spec.template.spec.securityContext.seccompProfile`](#obj-specoverridestatefulsetspectemplatespecsecuritycontextseccompprofile)
                * [`fn withLocalhostProfile(localhostProfile)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextseccompprofilewithlocalhostprofile)
                * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextseccompprofilewithtype)
              * [`obj spec.override.statefulSet.spec.template.spec.securityContext.sysctls`](#obj-specoverridestatefulsetspectemplatespecsecuritycontextsysctls)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextsysctlswithname)
                * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextsysctlswithvalue)
              * [`obj spec.override.statefulSet.spec.template.spec.securityContext.windowsOptions`](#obj-specoverridestatefulsetspectemplatespecsecuritycontextwindowsoptions)
                * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwindowsoptionswithgmsacredentialspec)
                * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwindowsoptionswithgmsacredentialspecname)
                * [`fn withHostProcess(hostProcess)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwindowsoptionswithhostprocess)
                * [`fn withRunAsUserName(runAsUserName)`](#fn-specoverridestatefulsetspectemplatespecsecuritycontextwindowsoptionswithrunasusername)
            * [`obj spec.override.statefulSet.spec.template.spec.tolerations`](#obj-specoverridestatefulsetspectemplatespectolerations)
              * [`fn withEffect(effect)`](#fn-specoverridestatefulsetspectemplatespectolerationswitheffect)
              * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespectolerationswithkey)
              * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespectolerationswithoperator)
              * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-specoverridestatefulsetspectemplatespectolerationswithtolerationseconds)
              * [`fn withValue(value)`](#fn-specoverridestatefulsetspectemplatespectolerationswithvalue)
            * [`obj spec.override.statefulSet.spec.template.spec.topologySpreadConstraints`](#obj-specoverridestatefulsetspectemplatespectopologyspreadconstraints)
              * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintswithmatchlabelkeys)
              * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintswithmatchlabelkeysmixin)
              * [`fn withMaxSkew(maxSkew)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintswithmaxskew)
              * [`fn withMinDomains(minDomains)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintswithmindomains)
              * [`fn withNodeAffinityPolicy(nodeAffinityPolicy)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintswithnodeaffinitypolicy)
              * [`fn withNodeTaintsPolicy(nodeTaintsPolicy)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintswithnodetaintspolicy)
              * [`fn withTopologyKey(topologyKey)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintswithtopologykey)
              * [`fn withWhenUnsatisfiable(whenUnsatisfiable)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintswithwhenunsatisfiable)
              * [`obj spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.labelSelector`](#obj-specoverridestatefulsetspectemplatespectopologyspreadconstraintslabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintslabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintslabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintslabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintslabelselectorwithmatchlabelsmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.labelSelector.matchExpressions`](#obj-specoverridestatefulsetspectemplatespectopologyspreadconstraintslabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintslabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintslabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintslabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespectopologyspreadconstraintslabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.override.statefulSet.spec.template.spec.volumes`](#obj-specoverridestatefulsetspectemplatespecvolumes)
              * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumeswithname)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.awsElasticBlockStore`](#obj-specoverridestatefulsetspectemplatespecvolumesawselasticblockstore)
                * [`fn withFsType(fsType)`](#fn-specoverridestatefulsetspectemplatespecvolumesawselasticblockstorewithfstype)
                * [`fn withPartition(partition)`](#fn-specoverridestatefulsetspectemplatespecvolumesawselasticblockstorewithpartition)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumesawselasticblockstorewithreadonly)
                * [`fn withVolumeID(volumeID)`](#fn-specoverridestatefulsetspectemplatespecvolumesawselasticblockstorewithvolumeid)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.azureDisk`](#obj-specoverridestatefulsetspectemplatespecvolumesazuredisk)
                * [`fn withCachingMode(cachingMode)`](#fn-specoverridestatefulsetspectemplatespecvolumesazurediskwithcachingmode)
                * [`fn withDiskName(diskName)`](#fn-specoverridestatefulsetspectemplatespecvolumesazurediskwithdiskname)
                * [`fn withDiskURI(diskURI)`](#fn-specoverridestatefulsetspectemplatespecvolumesazurediskwithdiskuri)
                * [`fn withFsType(fsType)`](#fn-specoverridestatefulsetspectemplatespecvolumesazurediskwithfstype)
                * [`fn withKind(kind)`](#fn-specoverridestatefulsetspectemplatespecvolumesazurediskwithkind)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumesazurediskwithreadonly)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.azureFile`](#obj-specoverridestatefulsetspectemplatespecvolumesazurefile)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumesazurefilewithreadonly)
                * [`fn withSecretName(secretName)`](#fn-specoverridestatefulsetspectemplatespecvolumesazurefilewithsecretname)
                * [`fn withShareName(shareName)`](#fn-specoverridestatefulsetspectemplatespecvolumesazurefilewithsharename)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.cephfs`](#obj-specoverridestatefulsetspectemplatespecvolumescephfs)
                * [`fn withMonitors(monitors)`](#fn-specoverridestatefulsetspectemplatespecvolumescephfswithmonitors)
                * [`fn withMonitorsMixin(monitors)`](#fn-specoverridestatefulsetspectemplatespecvolumescephfswithmonitorsmixin)
                * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecvolumescephfswithpath)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumescephfswithreadonly)
                * [`fn withSecretFile(secretFile)`](#fn-specoverridestatefulsetspectemplatespecvolumescephfswithsecretfile)
                * [`fn withUser(user)`](#fn-specoverridestatefulsetspectemplatespecvolumescephfswithuser)
                * [`obj spec.override.statefulSet.spec.template.spec.volumes.cephfs.secretRef`](#obj-specoverridestatefulsetspectemplatespecvolumescephfssecretref)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumescephfssecretrefwithname)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.cinder`](#obj-specoverridestatefulsetspectemplatespecvolumescinder)
                * [`fn withFsType(fsType)`](#fn-specoverridestatefulsetspectemplatespecvolumescinderwithfstype)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumescinderwithreadonly)
                * [`fn withVolumeID(volumeID)`](#fn-specoverridestatefulsetspectemplatespecvolumescinderwithvolumeid)
                * [`obj spec.override.statefulSet.spec.template.spec.volumes.cinder.secretRef`](#obj-specoverridestatefulsetspectemplatespecvolumescindersecretref)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumescindersecretrefwithname)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.configMap`](#obj-specoverridestatefulsetspectemplatespecvolumesconfigmap)
                * [`fn withDefaultMode(defaultMode)`](#fn-specoverridestatefulsetspectemplatespecvolumesconfigmapwithdefaultmode)
                * [`fn withItems(items)`](#fn-specoverridestatefulsetspectemplatespecvolumesconfigmapwithitems)
                * [`fn withItemsMixin(items)`](#fn-specoverridestatefulsetspectemplatespecvolumesconfigmapwithitemsmixin)
                * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumesconfigmapwithname)
                * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespecvolumesconfigmapwithoptional)
                * [`obj spec.override.statefulSet.spec.template.spec.volumes.configMap.items`](#obj-specoverridestatefulsetspectemplatespecvolumesconfigmapitems)
                  * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecvolumesconfigmapitemswithkey)
                  * [`fn withMode(mode)`](#fn-specoverridestatefulsetspectemplatespecvolumesconfigmapitemswithmode)
                  * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecvolumesconfigmapitemswithpath)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.csi`](#obj-specoverridestatefulsetspectemplatespecvolumescsi)
                * [`fn withDriver(driver)`](#fn-specoverridestatefulsetspectemplatespecvolumescsiwithdriver)
                * [`fn withFsType(fsType)`](#fn-specoverridestatefulsetspectemplatespecvolumescsiwithfstype)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumescsiwithreadonly)
                * [`fn withVolumeAttributes(volumeAttributes)`](#fn-specoverridestatefulsetspectemplatespecvolumescsiwithvolumeattributes)
                * [`fn withVolumeAttributesMixin(volumeAttributes)`](#fn-specoverridestatefulsetspectemplatespecvolumescsiwithvolumeattributesmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.volumes.csi.nodePublishSecretRef`](#obj-specoverridestatefulsetspectemplatespecvolumescsinodepublishsecretref)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumescsinodepublishsecretrefwithname)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.downwardAPI`](#obj-specoverridestatefulsetspectemplatespecvolumesdownwardapi)
                * [`fn withDefaultMode(defaultMode)`](#fn-specoverridestatefulsetspectemplatespecvolumesdownwardapiwithdefaultmode)
                * [`fn withItems(items)`](#fn-specoverridestatefulsetspectemplatespecvolumesdownwardapiwithitems)
                * [`fn withItemsMixin(items)`](#fn-specoverridestatefulsetspectemplatespecvolumesdownwardapiwithitemsmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.items`](#obj-specoverridestatefulsetspectemplatespecvolumesdownwardapiitems)
                  * [`fn withMode(mode)`](#fn-specoverridestatefulsetspectemplatespecvolumesdownwardapiitemswithmode)
                  * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecvolumesdownwardapiitemswithpath)
                  * [`obj spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.items.fieldRef`](#obj-specoverridestatefulsetspectemplatespecvolumesdownwardapiitemsfieldref)
                    * [`fn withApiVersion(apiVersion)`](#fn-specoverridestatefulsetspectemplatespecvolumesdownwardapiitemsfieldrefwithapiversion)
                    * [`fn withFieldPath(fieldPath)`](#fn-specoverridestatefulsetspectemplatespecvolumesdownwardapiitemsfieldrefwithfieldpath)
                  * [`obj spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.items.resourceFieldRef`](#obj-specoverridestatefulsetspectemplatespecvolumesdownwardapiitemsresourcefieldref)
                    * [`fn withContainerName(containerName)`](#fn-specoverridestatefulsetspectemplatespecvolumesdownwardapiitemsresourcefieldrefwithcontainername)
                    * [`fn withDivisor(divisor)`](#fn-specoverridestatefulsetspectemplatespecvolumesdownwardapiitemsresourcefieldrefwithdivisor)
                    * [`fn withResource(resource)`](#fn-specoverridestatefulsetspectemplatespecvolumesdownwardapiitemsresourcefieldrefwithresource)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.emptyDir`](#obj-specoverridestatefulsetspectemplatespecvolumesemptydir)
                * [`fn withMedium(medium)`](#fn-specoverridestatefulsetspectemplatespecvolumesemptydirwithmedium)
                * [`fn withSizeLimit(sizeLimit)`](#fn-specoverridestatefulsetspectemplatespecvolumesemptydirwithsizelimit)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral`](#obj-specoverridestatefulsetspectemplatespecvolumesephemeral)
                * [`obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate`](#obj-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplate)
                  * [`fn withMetadata(metadata)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatewithmetadata)
                  * [`fn withMetadataMixin(metadata)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatewithmetadatamixin)
                  * [`obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec`](#obj-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespec)
                    * [`fn withAccessModes(accessModes)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecwithaccessmodes)
                    * [`fn withAccessModesMixin(accessModes)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecwithaccessmodesmixin)
                    * [`fn withStorageClassName(storageClassName)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecwithstorageclassname)
                    * [`fn withVolumeAttributesClassName(volumeAttributesClassName)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecwithvolumeattributesclassname)
                    * [`fn withVolumeMode(volumeMode)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecwithvolumemode)
                    * [`fn withVolumeName(volumeName)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecwithvolumename)
                    * [`obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource`](#obj-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecdatasource)
                      * [`fn withApiGroup(apiGroup)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcewithapigroup)
                      * [`fn withKind(kind)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcewithkind)
                      * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcewithname)
                    * [`obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef`](#obj-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourceref)
                      * [`fn withApiGroup(apiGroup)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithapigroup)
                      * [`fn withKind(kind)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithkind)
                      * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithname)
                      * [`fn withNamespace(namespace)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithnamespace)
                    * [`obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources`](#obj-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecresources)
                      * [`fn withLimits(limits)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithlimits)
                      * [`fn withLimitsMixin(limits)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithlimitsmixin)
                      * [`fn withRequests(requests)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithrequests)
                      * [`fn withRequestsMixin(requests)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithrequestsmixin)
                    * [`obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector`](#obj-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecselector)
                      * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressions)
                      * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressionsmixin)
                      * [`fn withMatchLabels(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabels)
                      * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabelsmixin)
                      * [`obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions`](#obj-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressions)
                        * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithkey)
                        * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithoperator)
                        * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvalues)
                        * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvaluesmixin)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.fc`](#obj-specoverridestatefulsetspectemplatespecvolumesfc)
                * [`fn withFsType(fsType)`](#fn-specoverridestatefulsetspectemplatespecvolumesfcwithfstype)
                * [`fn withLun(lun)`](#fn-specoverridestatefulsetspectemplatespecvolumesfcwithlun)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumesfcwithreadonly)
                * [`fn withTargetWWNs(targetWWNs)`](#fn-specoverridestatefulsetspectemplatespecvolumesfcwithtargetwwns)
                * [`fn withTargetWWNsMixin(targetWWNs)`](#fn-specoverridestatefulsetspectemplatespecvolumesfcwithtargetwwnsmixin)
                * [`fn withWwids(wwids)`](#fn-specoverridestatefulsetspectemplatespecvolumesfcwithwwids)
                * [`fn withWwidsMixin(wwids)`](#fn-specoverridestatefulsetspectemplatespecvolumesfcwithwwidsmixin)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.flexVolume`](#obj-specoverridestatefulsetspectemplatespecvolumesflexvolume)
                * [`fn withDriver(driver)`](#fn-specoverridestatefulsetspectemplatespecvolumesflexvolumewithdriver)
                * [`fn withFsType(fsType)`](#fn-specoverridestatefulsetspectemplatespecvolumesflexvolumewithfstype)
                * [`fn withOptions(options)`](#fn-specoverridestatefulsetspectemplatespecvolumesflexvolumewithoptions)
                * [`fn withOptionsMixin(options)`](#fn-specoverridestatefulsetspectemplatespecvolumesflexvolumewithoptionsmixin)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumesflexvolumewithreadonly)
                * [`obj spec.override.statefulSet.spec.template.spec.volumes.flexVolume.secretRef`](#obj-specoverridestatefulsetspectemplatespecvolumesflexvolumesecretref)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumesflexvolumesecretrefwithname)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.flocker`](#obj-specoverridestatefulsetspectemplatespecvolumesflocker)
                * [`fn withDatasetName(datasetName)`](#fn-specoverridestatefulsetspectemplatespecvolumesflockerwithdatasetname)
                * [`fn withDatasetUUID(datasetUUID)`](#fn-specoverridestatefulsetspectemplatespecvolumesflockerwithdatasetuuid)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.gcePersistentDisk`](#obj-specoverridestatefulsetspectemplatespecvolumesgcepersistentdisk)
                * [`fn withFsType(fsType)`](#fn-specoverridestatefulsetspectemplatespecvolumesgcepersistentdiskwithfstype)
                * [`fn withPartition(partition)`](#fn-specoverridestatefulsetspectemplatespecvolumesgcepersistentdiskwithpartition)
                * [`fn withPdName(pdName)`](#fn-specoverridestatefulsetspectemplatespecvolumesgcepersistentdiskwithpdname)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumesgcepersistentdiskwithreadonly)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.gitRepo`](#obj-specoverridestatefulsetspectemplatespecvolumesgitrepo)
                * [`fn withDirectory(directory)`](#fn-specoverridestatefulsetspectemplatespecvolumesgitrepowithdirectory)
                * [`fn withRepository(repository)`](#fn-specoverridestatefulsetspectemplatespecvolumesgitrepowithrepository)
                * [`fn withRevision(revision)`](#fn-specoverridestatefulsetspectemplatespecvolumesgitrepowithrevision)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.glusterfs`](#obj-specoverridestatefulsetspectemplatespecvolumesglusterfs)
                * [`fn withEndpoints(endpoints)`](#fn-specoverridestatefulsetspectemplatespecvolumesglusterfswithendpoints)
                * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecvolumesglusterfswithpath)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumesglusterfswithreadonly)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.hostPath`](#obj-specoverridestatefulsetspectemplatespecvolumeshostpath)
                * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecvolumeshostpathwithpath)
                * [`fn withType(type)`](#fn-specoverridestatefulsetspectemplatespecvolumeshostpathwithtype)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.image`](#obj-specoverridestatefulsetspectemplatespecvolumesimage)
                * [`fn withPullPolicy(pullPolicy)`](#fn-specoverridestatefulsetspectemplatespecvolumesimagewithpullpolicy)
                * [`fn withReference(reference)`](#fn-specoverridestatefulsetspectemplatespecvolumesimagewithreference)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.iscsi`](#obj-specoverridestatefulsetspectemplatespecvolumesiscsi)
                * [`fn withChapAuthDiscovery(chapAuthDiscovery)`](#fn-specoverridestatefulsetspectemplatespecvolumesiscsiwithchapauthdiscovery)
                * [`fn withChapAuthSession(chapAuthSession)`](#fn-specoverridestatefulsetspectemplatespecvolumesiscsiwithchapauthsession)
                * [`fn withFsType(fsType)`](#fn-specoverridestatefulsetspectemplatespecvolumesiscsiwithfstype)
                * [`fn withInitiatorName(initiatorName)`](#fn-specoverridestatefulsetspectemplatespecvolumesiscsiwithinitiatorname)
                * [`fn withIqn(iqn)`](#fn-specoverridestatefulsetspectemplatespecvolumesiscsiwithiqn)
                * [`fn withIscsiInterface(iscsiInterface)`](#fn-specoverridestatefulsetspectemplatespecvolumesiscsiwithiscsiinterface)
                * [`fn withLun(lun)`](#fn-specoverridestatefulsetspectemplatespecvolumesiscsiwithlun)
                * [`fn withPortals(portals)`](#fn-specoverridestatefulsetspectemplatespecvolumesiscsiwithportals)
                * [`fn withPortalsMixin(portals)`](#fn-specoverridestatefulsetspectemplatespecvolumesiscsiwithportalsmixin)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumesiscsiwithreadonly)
                * [`fn withTargetPortal(targetPortal)`](#fn-specoverridestatefulsetspectemplatespecvolumesiscsiwithtargetportal)
                * [`obj spec.override.statefulSet.spec.template.spec.volumes.iscsi.secretRef`](#obj-specoverridestatefulsetspectemplatespecvolumesiscsisecretref)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumesiscsisecretrefwithname)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.nfs`](#obj-specoverridestatefulsetspectemplatespecvolumesnfs)
                * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecvolumesnfswithpath)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumesnfswithreadonly)
                * [`fn withServer(server)`](#fn-specoverridestatefulsetspectemplatespecvolumesnfswithserver)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.persistentVolumeClaim`](#obj-specoverridestatefulsetspectemplatespecvolumespersistentvolumeclaim)
                * [`fn withClaimName(claimName)`](#fn-specoverridestatefulsetspectemplatespecvolumespersistentvolumeclaimwithclaimname)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumespersistentvolumeclaimwithreadonly)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.photonPersistentDisk`](#obj-specoverridestatefulsetspectemplatespecvolumesphotonpersistentdisk)
                * [`fn withFsType(fsType)`](#fn-specoverridestatefulsetspectemplatespecvolumesphotonpersistentdiskwithfstype)
                * [`fn withPdID(pdID)`](#fn-specoverridestatefulsetspectemplatespecvolumesphotonpersistentdiskwithpdid)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.portworxVolume`](#obj-specoverridestatefulsetspectemplatespecvolumesportworxvolume)
                * [`fn withFsType(fsType)`](#fn-specoverridestatefulsetspectemplatespecvolumesportworxvolumewithfstype)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumesportworxvolumewithreadonly)
                * [`fn withVolumeID(volumeID)`](#fn-specoverridestatefulsetspectemplatespecvolumesportworxvolumewithvolumeid)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.projected`](#obj-specoverridestatefulsetspectemplatespecvolumesprojected)
                * [`fn withDefaultMode(defaultMode)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedwithdefaultmode)
                * [`fn withSources(sources)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedwithsources)
                * [`fn withSourcesMixin(sources)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedwithsourcesmixin)
                * [`obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources`](#obj-specoverridestatefulsetspectemplatespecvolumesprojectedsources)
                  * [`obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle`](#obj-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundle)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundlewithname)
                    * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundlewithoptional)
                    * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundlewithpath)
                    * [`fn withSignerName(signerName)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundlewithsignername)
                    * [`obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector`](#obj-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundlelabelselector)
                      * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressions)
                      * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressionsmixin)
                      * [`fn withMatchLabels(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabels)
                      * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabelsmixin)
                      * [`obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions`](#obj-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressions)
                        * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithkey)
                        * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithoperator)
                        * [`fn withValues(values)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvalues)
                        * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvaluesmixin)
                  * [`obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.configMap`](#obj-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesconfigmap)
                    * [`fn withItems(items)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesconfigmapwithitems)
                    * [`fn withItemsMixin(items)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesconfigmapwithitemsmixin)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesconfigmapwithname)
                    * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesconfigmapwithoptional)
                    * [`obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.configMap.items`](#obj-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesconfigmapitems)
                      * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesconfigmapitemswithkey)
                      * [`fn withMode(mode)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesconfigmapitemswithmode)
                      * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesconfigmapitemswithpath)
                  * [`obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI`](#obj-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesdownwardapi)
                    * [`fn withItems(items)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesdownwardapiwithitems)
                    * [`fn withItemsMixin(items)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesdownwardapiwithitemsmixin)
                    * [`obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.items`](#obj-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesdownwardapiitems)
                      * [`fn withMode(mode)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesdownwardapiitemswithmode)
                      * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesdownwardapiitemswithpath)
                      * [`obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.items.fieldRef`](#obj-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesdownwardapiitemsfieldref)
                        * [`fn withApiVersion(apiVersion)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesdownwardapiitemsfieldrefwithapiversion)
                        * [`fn withFieldPath(fieldPath)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesdownwardapiitemsfieldrefwithfieldpath)
                      * [`obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef`](#obj-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldref)
                        * [`fn withContainerName(containerName)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithcontainername)
                        * [`fn withDivisor(divisor)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithdivisor)
                        * [`fn withResource(resource)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithresource)
                  * [`obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.secret`](#obj-specoverridestatefulsetspectemplatespecvolumesprojectedsourcessecret)
                    * [`fn withItems(items)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcessecretwithitems)
                    * [`fn withItemsMixin(items)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcessecretwithitemsmixin)
                    * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcessecretwithname)
                    * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcessecretwithoptional)
                    * [`obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.secret.items`](#obj-specoverridestatefulsetspectemplatespecvolumesprojectedsourcessecretitems)
                      * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcessecretitemswithkey)
                      * [`fn withMode(mode)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcessecretitemswithmode)
                      * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcessecretitemswithpath)
                  * [`obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.serviceAccountToken`](#obj-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesserviceaccounttoken)
                    * [`fn withAudience(audience)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesserviceaccounttokenwithaudience)
                    * [`fn withExpirationSeconds(expirationSeconds)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesserviceaccounttokenwithexpirationseconds)
                    * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecvolumesprojectedsourcesserviceaccounttokenwithpath)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.quobyte`](#obj-specoverridestatefulsetspectemplatespecvolumesquobyte)
                * [`fn withGroup(group)`](#fn-specoverridestatefulsetspectemplatespecvolumesquobytewithgroup)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumesquobytewithreadonly)
                * [`fn withRegistry(registry)`](#fn-specoverridestatefulsetspectemplatespecvolumesquobytewithregistry)
                * [`fn withTenant(tenant)`](#fn-specoverridestatefulsetspectemplatespecvolumesquobytewithtenant)
                * [`fn withUser(user)`](#fn-specoverridestatefulsetspectemplatespecvolumesquobytewithuser)
                * [`fn withVolume(volume)`](#fn-specoverridestatefulsetspectemplatespecvolumesquobytewithvolume)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.rbd`](#obj-specoverridestatefulsetspectemplatespecvolumesrbd)
                * [`fn withFsType(fsType)`](#fn-specoverridestatefulsetspectemplatespecvolumesrbdwithfstype)
                * [`fn withImage(image)`](#fn-specoverridestatefulsetspectemplatespecvolumesrbdwithimage)
                * [`fn withKeyring(keyring)`](#fn-specoverridestatefulsetspectemplatespecvolumesrbdwithkeyring)
                * [`fn withMonitors(monitors)`](#fn-specoverridestatefulsetspectemplatespecvolumesrbdwithmonitors)
                * [`fn withMonitorsMixin(monitors)`](#fn-specoverridestatefulsetspectemplatespecvolumesrbdwithmonitorsmixin)
                * [`fn withPool(pool)`](#fn-specoverridestatefulsetspectemplatespecvolumesrbdwithpool)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumesrbdwithreadonly)
                * [`fn withUser(user)`](#fn-specoverridestatefulsetspectemplatespecvolumesrbdwithuser)
                * [`obj spec.override.statefulSet.spec.template.spec.volumes.rbd.secretRef`](#obj-specoverridestatefulsetspectemplatespecvolumesrbdsecretref)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumesrbdsecretrefwithname)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.scaleIO`](#obj-specoverridestatefulsetspectemplatespecvolumesscaleio)
                * [`fn withFsType(fsType)`](#fn-specoverridestatefulsetspectemplatespecvolumesscaleiowithfstype)
                * [`fn withGateway(gateway)`](#fn-specoverridestatefulsetspectemplatespecvolumesscaleiowithgateway)
                * [`fn withProtectionDomain(protectionDomain)`](#fn-specoverridestatefulsetspectemplatespecvolumesscaleiowithprotectiondomain)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumesscaleiowithreadonly)
                * [`fn withSslEnabled(sslEnabled)`](#fn-specoverridestatefulsetspectemplatespecvolumesscaleiowithsslenabled)
                * [`fn withStorageMode(storageMode)`](#fn-specoverridestatefulsetspectemplatespecvolumesscaleiowithstoragemode)
                * [`fn withStoragePool(storagePool)`](#fn-specoverridestatefulsetspectemplatespecvolumesscaleiowithstoragepool)
                * [`fn withSystem(system)`](#fn-specoverridestatefulsetspectemplatespecvolumesscaleiowithsystem)
                * [`fn withVolumeName(volumeName)`](#fn-specoverridestatefulsetspectemplatespecvolumesscaleiowithvolumename)
                * [`obj spec.override.statefulSet.spec.template.spec.volumes.scaleIO.secretRef`](#obj-specoverridestatefulsetspectemplatespecvolumesscaleiosecretref)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumesscaleiosecretrefwithname)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.secret`](#obj-specoverridestatefulsetspectemplatespecvolumessecret)
                * [`fn withDefaultMode(defaultMode)`](#fn-specoverridestatefulsetspectemplatespecvolumessecretwithdefaultmode)
                * [`fn withItems(items)`](#fn-specoverridestatefulsetspectemplatespecvolumessecretwithitems)
                * [`fn withItemsMixin(items)`](#fn-specoverridestatefulsetspectemplatespecvolumessecretwithitemsmixin)
                * [`fn withOptional(optional)`](#fn-specoverridestatefulsetspectemplatespecvolumessecretwithoptional)
                * [`fn withSecretName(secretName)`](#fn-specoverridestatefulsetspectemplatespecvolumessecretwithsecretname)
                * [`obj spec.override.statefulSet.spec.template.spec.volumes.secret.items`](#obj-specoverridestatefulsetspectemplatespecvolumessecretitems)
                  * [`fn withKey(key)`](#fn-specoverridestatefulsetspectemplatespecvolumessecretitemswithkey)
                  * [`fn withMode(mode)`](#fn-specoverridestatefulsetspectemplatespecvolumessecretitemswithmode)
                  * [`fn withPath(path)`](#fn-specoverridestatefulsetspectemplatespecvolumessecretitemswithpath)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.storageos`](#obj-specoverridestatefulsetspectemplatespecvolumesstorageos)
                * [`fn withFsType(fsType)`](#fn-specoverridestatefulsetspectemplatespecvolumesstorageoswithfstype)
                * [`fn withReadOnly(readOnly)`](#fn-specoverridestatefulsetspectemplatespecvolumesstorageoswithreadonly)
                * [`fn withVolumeName(volumeName)`](#fn-specoverridestatefulsetspectemplatespecvolumesstorageoswithvolumename)
                * [`fn withVolumeNamespace(volumeNamespace)`](#fn-specoverridestatefulsetspectemplatespecvolumesstorageoswithvolumenamespace)
                * [`obj spec.override.statefulSet.spec.template.spec.volumes.storageos.secretRef`](#obj-specoverridestatefulsetspectemplatespecvolumesstorageossecretref)
                  * [`fn withName(name)`](#fn-specoverridestatefulsetspectemplatespecvolumesstorageossecretrefwithname)
              * [`obj spec.override.statefulSet.spec.template.spec.volumes.vsphereVolume`](#obj-specoverridestatefulsetspectemplatespecvolumesvspherevolume)
                * [`fn withFsType(fsType)`](#fn-specoverridestatefulsetspectemplatespecvolumesvspherevolumewithfstype)
                * [`fn withStoragePolicyID(storagePolicyID)`](#fn-specoverridestatefulsetspectemplatespecvolumesvspherevolumewithstoragepolicyid)
                * [`fn withStoragePolicyName(storagePolicyName)`](#fn-specoverridestatefulsetspectemplatespecvolumesvspherevolumewithstoragepolicyname)
                * [`fn withVolumePath(volumePath)`](#fn-specoverridestatefulsetspectemplatespecvolumesvspherevolumewithvolumepath)
        * [`obj spec.override.statefulSet.spec.updateStrategy`](#obj-specoverridestatefulsetspecupdatestrategy)
          * [`fn withType(type)`](#fn-specoverridestatefulsetspecupdatestrategywithtype)
          * [`obj spec.override.statefulSet.spec.updateStrategy.rollingUpdate`](#obj-specoverridestatefulsetspecupdatestrategyrollingupdate)
            * [`fn withMaxUnavailable(maxUnavailable)`](#fn-specoverridestatefulsetspecupdatestrategyrollingupdatewithmaxunavailable)
            * [`fn withPartition(partition)`](#fn-specoverridestatefulsetspecupdatestrategyrollingupdatewithpartition)
        * [`obj spec.override.statefulSet.spec.volumeClaimTemplates`](#obj-specoverridestatefulsetspecvolumeclaimtemplates)
          * [`fn withApiVersion(apiVersion)`](#fn-specoverridestatefulsetspecvolumeclaimtemplateswithapiversion)
          * [`fn withKind(kind)`](#fn-specoverridestatefulsetspecvolumeclaimtemplateswithkind)
          * [`obj spec.override.statefulSet.spec.volumeClaimTemplates.metadata`](#obj-specoverridestatefulsetspecvolumeclaimtemplatesmetadata)
            * [`fn withAnnotations(annotations)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesmetadatawithannotations)
            * [`fn withAnnotationsMixin(annotations)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesmetadatawithannotationsmixin)
            * [`fn withLabels(labels)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesmetadatawithlabels)
            * [`fn withLabelsMixin(labels)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesmetadatawithlabelsmixin)
            * [`fn withName(name)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesmetadatawithname)
            * [`fn withNamespace(namespace)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesmetadatawithnamespace)
          * [`obj spec.override.statefulSet.spec.volumeClaimTemplates.spec`](#obj-specoverridestatefulsetspecvolumeclaimtemplatesspec)
            * [`fn withAccessModes(accessModes)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecwithaccessmodes)
            * [`fn withAccessModesMixin(accessModes)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecwithaccessmodesmixin)
            * [`fn withStorageClassName(storageClassName)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecwithstorageclassname)
            * [`fn withVolumeAttributesClassName(volumeAttributesClassName)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecwithvolumeattributesclassname)
            * [`fn withVolumeMode(volumeMode)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecwithvolumemode)
            * [`fn withVolumeName(volumeName)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecwithvolumename)
            * [`obj spec.override.statefulSet.spec.volumeClaimTemplates.spec.dataSource`](#obj-specoverridestatefulsetspecvolumeclaimtemplatesspecdatasource)
              * [`fn withApiGroup(apiGroup)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecdatasourcewithapigroup)
              * [`fn withKind(kind)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecdatasourcewithkind)
              * [`fn withName(name)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecdatasourcewithname)
            * [`obj spec.override.statefulSet.spec.volumeClaimTemplates.spec.dataSourceRef`](#obj-specoverridestatefulsetspecvolumeclaimtemplatesspecdatasourceref)
              * [`fn withApiGroup(apiGroup)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecdatasourcerefwithapigroup)
              * [`fn withKind(kind)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecdatasourcerefwithkind)
              * [`fn withName(name)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecdatasourcerefwithname)
              * [`fn withNamespace(namespace)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecdatasourcerefwithnamespace)
            * [`obj spec.override.statefulSet.spec.volumeClaimTemplates.spec.resources`](#obj-specoverridestatefulsetspecvolumeclaimtemplatesspecresources)
              * [`fn withLimits(limits)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecresourceswithlimits)
              * [`fn withLimitsMixin(limits)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecresourceswithlimitsmixin)
              * [`fn withRequests(requests)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecresourceswithrequests)
              * [`fn withRequestsMixin(requests)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecresourceswithrequestsmixin)
            * [`obj spec.override.statefulSet.spec.volumeClaimTemplates.spec.selector`](#obj-specoverridestatefulsetspecvolumeclaimtemplatesspecselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecselectorwithmatchlabelsmixin)
              * [`obj spec.override.statefulSet.spec.volumeClaimTemplates.spec.selector.matchExpressions`](#obj-specoverridestatefulsetspecvolumeclaimtemplatesspecselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specoverridestatefulsetspecvolumeclaimtemplatesspecselectormatchexpressionswithvaluesmixin)
  * [`obj spec.persistence`](#obj-specpersistence)
    * [`fn withStorage(storage)`](#fn-specpersistencewithstorage)
    * [`fn withStorageClassName(storageClassName)`](#fn-specpersistencewithstorageclassname)
  * [`obj spec.rabbitmq`](#obj-specrabbitmq)
    * [`fn withAdditionalConfig(additionalConfig)`](#fn-specrabbitmqwithadditionalconfig)
    * [`fn withAdditionalPlugins(additionalPlugins)`](#fn-specrabbitmqwithadditionalplugins)
    * [`fn withAdditionalPluginsMixin(additionalPlugins)`](#fn-specrabbitmqwithadditionalpluginsmixin)
    * [`fn withAdvancedConfig(advancedConfig)`](#fn-specrabbitmqwithadvancedconfig)
    * [`fn withEnvConfig(envConfig)`](#fn-specrabbitmqwithenvconfig)
    * [`fn withErlangInetConfig(erlangInetConfig)`](#fn-specrabbitmqwitherlanginetconfig)
  * [`obj spec.resources`](#obj-specresources)
    * [`fn withClaims(claims)`](#fn-specresourceswithclaims)
    * [`fn withClaimsMixin(claims)`](#fn-specresourceswithclaimsmixin)
    * [`fn withLimits(limits)`](#fn-specresourceswithlimits)
    * [`fn withLimitsMixin(limits)`](#fn-specresourceswithlimitsmixin)
    * [`fn withRequests(requests)`](#fn-specresourceswithrequests)
    * [`fn withRequestsMixin(requests)`](#fn-specresourceswithrequestsmixin)
    * [`obj spec.resources.claims`](#obj-specresourcesclaims)
      * [`fn withName(name)`](#fn-specresourcesclaimswithname)
      * [`fn withRequest(request)`](#fn-specresourcesclaimswithrequest)
  * [`obj spec.secretBackend`](#obj-specsecretbackend)
    * [`obj spec.secretBackend.externalSecret`](#obj-specsecretbackendexternalsecret)
      * [`fn withName(name)`](#fn-specsecretbackendexternalsecretwithname)
    * [`obj spec.secretBackend.vault`](#obj-specsecretbackendvault)
      * [`fn withAnnotations(annotations)`](#fn-specsecretbackendvaultwithannotations)
      * [`fn withAnnotationsMixin(annotations)`](#fn-specsecretbackendvaultwithannotationsmixin)
      * [`fn withDefaultUserPath(defaultUserPath)`](#fn-specsecretbackendvaultwithdefaultuserpath)
      * [`fn withDefaultUserUpdaterImage(defaultUserUpdaterImage)`](#fn-specsecretbackendvaultwithdefaultuserupdaterimage)
      * [`fn withRole(role)`](#fn-specsecretbackendvaultwithrole)
      * [`obj spec.secretBackend.vault.tls`](#obj-specsecretbackendvaulttls)
        * [`fn withAltNames(altNames)`](#fn-specsecretbackendvaulttlswithaltnames)
        * [`fn withCommonName(commonName)`](#fn-specsecretbackendvaulttlswithcommonname)
        * [`fn withIpSans(ipSans)`](#fn-specsecretbackendvaulttlswithipsans)
        * [`fn withPkiIssuerPath(pkiIssuerPath)`](#fn-specsecretbackendvaulttlswithpkiissuerpath)
        * [`fn withPkiRootPath(pkiRootPath)`](#fn-specsecretbackendvaulttlswithpkirootpath)
  * [`obj spec.service`](#obj-specservice)
    * [`fn withAnnotations(annotations)`](#fn-specservicewithannotations)
    * [`fn withAnnotationsMixin(annotations)`](#fn-specservicewithannotationsmixin)
    * [`fn withIpFamilyPolicy(ipFamilyPolicy)`](#fn-specservicewithipfamilypolicy)
    * [`fn withLabels(labels)`](#fn-specservicewithlabels)
    * [`fn withLabelsMixin(labels)`](#fn-specservicewithlabelsmixin)
    * [`fn withType(type)`](#fn-specservicewithtype)
  * [`obj spec.tls`](#obj-spectls)
    * [`fn withCaSecretName(caSecretName)`](#fn-spectlswithcasecretname)
    * [`fn withDisableNonTLSListeners(disableNonTLSListeners)`](#fn-spectlswithdisablenontlslisteners)
    * [`fn withSecretName(secretName)`](#fn-spectlswithsecretname)
  * [`obj spec.tolerations`](#obj-spectolerations)
    * [`fn withEffect(effect)`](#fn-spectolerationswitheffect)
    * [`fn withKey(key)`](#fn-spectolerationswithkey)
    * [`fn withOperator(operator)`](#fn-spectolerationswithoperator)
    * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-spectolerationswithtolerationseconds)
    * [`fn withValue(value)`](#fn-spectolerationswithvalue)

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

### fn spec.withDelayStartSeconds

```ts
withDelayStartSeconds(delayStartSeconds)
```

"DelayStartSeconds is the time the init container (`setup-container`) will sleep before terminating.\nThis effectively delays the time between starting the Pod and starting the `rabbitmq` container.\nRabbitMQ relies on up-to-date DNS entries early during peer discovery.\nThe purpose of this artificial delay is to ensure that DNS entries are up-to-date when booting RabbitMQ.\nFor more information, see https://github.com/kubernetes/kubernetes/issues/92559\nIf your Kubernetes DNS backend is configured with a low DNS cache value or publishes not ready addresses\npromptly, you can decrase this value or set it to 0."

### fn spec.withImage

```ts
withImage(image)
```

"Image is the name of the RabbitMQ docker image to use for RabbitMQ nodes in the RabbitmqCluster.\nMust be provided together with ImagePullSecrets in order to use an image in a private registry."

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

"Replicas is the number of nodes in the RabbitMQ cluster. Each node is deployed as a Replica in a StatefulSet. Only 1, 3, 5 replicas clusters are tested.\nThis value should be an odd number to ensure the resultant cluster can establish exactly one quorum of nodes\nin the event of a fragmenting network partition."

### fn spec.withSkipPostDeploySteps

```ts
withSkipPostDeploySteps(skipPostDeploySteps)
```

"If unset, or set to false, the cluster will run `rabbitmq-queues rebalance all` whenever the cluster is updated.\nSet to true to prevent the operator rebalancing queue leaders after a cluster update.\nHas no effect if the cluster only consists of one node.\nFor more information, see https://www.rabbitmq.com/rabbitmq-queues.8.html#rebalance"

### fn spec.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```

"TerminationGracePeriodSeconds is the timeout that each rabbitmqcluster pod will have to terminate gracefully.\nIt defaults to 604800 seconds ( a week long) to ensure that the container preStop lifecycle hook can finish running.\nFor more information, see: https://github.com/rabbitmq/cluster-operator/blob/main/docs/design/20200520-graceful-pod-termination.md"

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

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node matches the corresponding matchExpressions; the\nnode(s) with the highest sum are the most preferred."

### fn spec.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node matches the corresponding matchExpressions; the\nnode(s) with the highest sum are the most preferred."

**Note:** This function appends passed data to existing values

## obj spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node matches the corresponding matchExpressions; the\nnode(s) with the highest sum are the most preferred."

### fn spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```

"Weight associated with matching the corresponding nodeSelectorTerm, in the range 1-100."

## obj spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference

"A node selector term, associated with the corresponding weight."

### fn spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"A list of node selector requirements by node's labels."

### fn spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"A list of node selector requirements by node's labels."

**Note:** This function appends passed data to existing values

### fn spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```

"A list of node selector requirements by node's fields."

### fn spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```

"A list of node selector requirements by node's fields."

**Note:** This function appends passed data to existing values

## obj spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions

"A list of node selector requirements by node's labels."

### fn spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```

"The label key that the selector applies to."

### fn spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```

"Represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists, DoesNotExist. Gt, and Lt."

### fn spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

### fn spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

**Note:** This function appends passed data to existing values

## obj spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields

"A list of node selector requirements by node's fields."

### fn spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```

"The label key that the selector applies to."

### fn spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```

"Represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists, DoesNotExist. Gt, and Lt."

### fn spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

### fn spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

**Note:** This function appends passed data to existing values

## obj spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution

"If the affinity requirements specified by this field are not met at\nscheduling time, the pod will not be scheduled onto the node.\nIf the affinity requirements specified by this field cease to be met\nat some point during pod execution (e.g. due to an update), the system\nmay or may not try to eventually evict the pod from its node."

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

## obj spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms

"Required. A list of node selector terms. The terms are ORed."

### fn spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"A list of node selector requirements by node's labels."

### fn spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"A list of node selector requirements by node's labels."

**Note:** This function appends passed data to existing values

### fn spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```

"A list of node selector requirements by node's fields."

### fn spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```

"A list of node selector requirements by node's fields."

**Note:** This function appends passed data to existing values

## obj spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions

"A list of node selector requirements by node's labels."

### fn spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```

"The label key that the selector applies to."

### fn spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```

"Represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists, DoesNotExist. Gt, and Lt."

### fn spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

### fn spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

**Note:** This function appends passed data to existing values

## obj spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields

"A list of node selector requirements by node's fields."

### fn spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```

"The label key that the selector applies to."

### fn spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```

"Represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists, DoesNotExist. Gt, and Lt."

### fn spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

### fn spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAffinity

"Describes pod affinity scheduling rules (e.g. co-locate this pod in the same node, zone, etc. as some other pod(s))."

### fn spec.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node has pods which matches the corresponding podAffinityTerm; the\nnode(s) with the highest sum are the most preferred."

### fn spec.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node has pods which matches the corresponding podAffinityTerm; the\nnode(s) with the highest sum are the most preferred."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```

"If the affinity requirements specified by this field are not met at\nscheduling time, the pod will not be scheduled onto the node.\nIf the affinity requirements specified by this field cease to be met\nat some point during pod execution (e.g. due to a pod label update), the\nsystem may or may not try to eventually evict the pod from its node.\nWhen there are multiple elements, the lists of nodes corresponding to each\npodAffinityTerm are intersected, i.e. all terms must be satisfied."

### fn spec.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```

"If the affinity requirements specified by this field are not met at\nscheduling time, the pod will not be scheduled onto the node.\nIf the affinity requirements specified by this field cease to be met\nat some point during pod execution (e.g. due to a pod label update), the\nsystem may or may not try to eventually evict the pod from its node.\nWhen there are multiple elements, the lists of nodes corresponding to each\npodAffinityTerm are intersected, i.e. all terms must be satisfied."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node has pods which matches the corresponding podAffinityTerm; the\nnode(s) with the highest sum are the most preferred."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```

"weight associated with matching the corresponding podAffinityTerm,\nin the range 1-100."

## obj spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm

"Required. A pod affinity term, associated with the corresponding weight."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```

"This pod should be co-located (affinity) or not co-located (anti-affinity) with the pods matching\nthe labelSelector in the specified namespaces, where co-located is defined as running on a node\nwhose value of the label with key topologyKey matches that of any node on which any of the\nselected pods is running.\nEmpty topologyKey is not allowed."

## obj spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector

"A label query over a set of resources, in this case pods.\nIf it's null, this PodAffinityTerm matches with no Pods."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector

"A label query over the set of namespaces that the term applies to.\nThe term is applied to the union of the namespaces selected by this field\nand the ones listed in the namespaces field.\nnull selector and null or empty namespaces list means \"this pod's namespace\".\nAn empty selector ({}) matches all namespaces."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution

"If the affinity requirements specified by this field are not met at\nscheduling time, the pod will not be scheduled onto the node.\nIf the affinity requirements specified by this field cease to be met\nat some point during pod execution (e.g. due to a pod label update), the\nsystem may or may not try to eventually evict the pod from its node.\nWhen there are multiple elements, the lists of nodes corresponding to each\npodAffinityTerm are intersected, i.e. all terms must be satisfied."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```

"This pod should be co-located (affinity) or not co-located (anti-affinity) with the pods matching\nthe labelSelector in the specified namespaces, where co-located is defined as running on a node\nwhose value of the label with key topologyKey matches that of any node on which any of the\nselected pods is running.\nEmpty topologyKey is not allowed."

## obj spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector

"A label query over a set of resources, in this case pods.\nIf it's null, this PodAffinityTerm matches with no Pods."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector

"A label query over the set of namespaces that the term applies to.\nThe term is applied to the union of the namespaces selected by this field\nand the ones listed in the namespaces field.\nnull selector and null or empty namespaces list means \"this pod's namespace\".\nAn empty selector ({}) matches all namespaces."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAntiAffinity

"Describes pod anti-affinity scheduling rules (e.g. avoid putting this pod in the same node, zone, etc. as some other pod(s))."

### fn spec.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe anti-affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling anti-affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node has pods which matches the corresponding podAffinityTerm; the\nnode(s) with the highest sum are the most preferred."

### fn spec.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe anti-affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling anti-affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node has pods which matches the corresponding podAffinityTerm; the\nnode(s) with the highest sum are the most preferred."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```

"If the anti-affinity requirements specified by this field are not met at\nscheduling time, the pod will not be scheduled onto the node.\nIf the anti-affinity requirements specified by this field cease to be met\nat some point during pod execution (e.g. due to a pod label update), the\nsystem may or may not try to eventually evict the pod from its node.\nWhen there are multiple elements, the lists of nodes corresponding to each\npodAffinityTerm are intersected, i.e. all terms must be satisfied."

### fn spec.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```

"If the anti-affinity requirements specified by this field are not met at\nscheduling time, the pod will not be scheduled onto the node.\nIf the anti-affinity requirements specified by this field cease to be met\nat some point during pod execution (e.g. due to a pod label update), the\nsystem may or may not try to eventually evict the pod from its node.\nWhen there are multiple elements, the lists of nodes corresponding to each\npodAffinityTerm are intersected, i.e. all terms must be satisfied."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe anti-affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling anti-affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node has pods which matches the corresponding podAffinityTerm; the\nnode(s) with the highest sum are the most preferred."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```

"weight associated with matching the corresponding podAffinityTerm,\nin the range 1-100."

## obj spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm

"Required. A pod affinity term, associated with the corresponding weight."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```

"This pod should be co-located (affinity) or not co-located (anti-affinity) with the pods matching\nthe labelSelector in the specified namespaces, where co-located is defined as running on a node\nwhose value of the label with key topologyKey matches that of any node on which any of the\nselected pods is running.\nEmpty topologyKey is not allowed."

## obj spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector

"A label query over a set of resources, in this case pods.\nIf it's null, this PodAffinityTerm matches with no Pods."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector

"A label query over the set of namespaces that the term applies to.\nThe term is applied to the union of the namespaces selected by this field\nand the ones listed in the namespaces field.\nnull selector and null or empty namespaces list means \"this pod's namespace\".\nAn empty selector ({}) matches all namespaces."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution

"If the anti-affinity requirements specified by this field are not met at\nscheduling time, the pod will not be scheduled onto the node.\nIf the anti-affinity requirements specified by this field cease to be met\nat some point during pod execution (e.g. due to a pod label update), the\nsystem may or may not try to eventually evict the pod from its node.\nWhen there are multiple elements, the lists of nodes corresponding to each\npodAffinityTerm are intersected, i.e. all terms must be satisfied."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```

"This pod should be co-located (affinity) or not co-located (anti-affinity) with the pods matching\nthe labelSelector in the specified namespaces, where co-located is defined as running on a node\nwhose value of the label with key topologyKey matches that of any node on which any of the\nselected pods is running.\nEmpty topologyKey is not allowed."

## obj spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector

"A label query over a set of resources, in this case pods.\nIf it's null, this PodAffinityTerm matches with no Pods."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector

"A label query over the set of namespaces that the term applies to.\nThe term is applied to the union of the namespaces selected by this field\nand the ones listed in the namespaces field.\nnull selector and null or empty namespaces list means \"this pod's namespace\".\nAn empty selector ({}) matches all namespaces."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.imagePullSecrets

"List of Secret resource containing access credentials to the registry for the RabbitMQ image. Required if the docker registry is private."

### fn spec.imagePullSecrets.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

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



### fn spec.override.service.spec.withInternalTrafficPolicy

```ts
withInternalTrafficPolicy(internalTrafficPolicy)
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



### fn spec.override.service.spec.withLoadBalancerClass

```ts
withLoadBalancerClass(loadBalancerClass)
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



### fn spec.override.service.spec.withTrafficDistribution

```ts
withTrafficDistribution(trafficDistribution)
```



### fn spec.override.service.spec.withType

```ts
withType(type)
```



## obj spec.override.service.spec.ports



### fn spec.override.service.spec.ports.withAppProtocol

```ts
withAppProtocol(appProtocol)
```



### fn spec.override.service.spec.ports.withName

```ts
withName(name)
```



### fn spec.override.service.spec.ports.withNodePort

```ts
withNodePort(nodePort)
```



### fn spec.override.service.spec.ports.withPort

```ts
withPort(port)
```



### fn spec.override.service.spec.ports.withProtocol

```ts
withProtocol(protocol)
```



### fn spec.override.service.spec.ports.withTargetPort

```ts
withTargetPort(targetPort)
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



### fn spec.override.statefulSet.spec.withMinReadySeconds

```ts
withMinReadySeconds(minReadySeconds)
```



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

## obj spec.override.statefulSet.spec.persistentVolumeClaimRetentionPolicy



### fn spec.override.statefulSet.spec.persistentVolumeClaimRetentionPolicy.withWhenDeleted

```ts
withWhenDeleted(whenDeleted)
```



### fn spec.override.statefulSet.spec.persistentVolumeClaimRetentionPolicy.withWhenScaled

```ts
withWhenScaled(whenScaled)
```



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

## obj spec.override.statefulSet.spec.selector.matchExpressions



### fn spec.override.statefulSet.spec.selector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.selector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
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



### fn spec.override.statefulSet.spec.template.spec.withHostUsers

```ts
withHostUsers(hostUsers)
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

### fn spec.override.statefulSet.spec.template.spec.withResourceClaims

```ts
withResourceClaims(resourceClaims)
```



### fn spec.override.statefulSet.spec.template.spec.withResourceClaimsMixin

```ts
withResourceClaimsMixin(resourceClaims)
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



### fn spec.override.statefulSet.spec.template.spec.withSchedulingGates

```ts
withSchedulingGates(schedulingGates)
```



### fn spec.override.statefulSet.spec.template.spec.withSchedulingGatesMixin

```ts
withSchedulingGatesMixin(schedulingGates)
```



**Note:** This function appends passed data to existing values

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

## obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
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

## obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
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

## obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
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

## obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.containers



### fn spec.override.statefulSet.spec.template.spec.containers.withArgs

```ts
withArgs(args)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.withEnv

```ts
withEnv(env)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.withImage

```ts
withImage(image)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withPorts

```ts
withPorts(ports)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withPortsMixin

```ts
withPortsMixin(ports)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.withResizePolicy

```ts
withResizePolicy(resizePolicy)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withResizePolicyMixin

```ts
withResizePolicyMixin(resizePolicy)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withStdin

```ts
withStdin(stdin)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withStdinOnce

```ts
withStdinOnce(stdinOnce)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withTerminationMessagePath

```ts
withTerminationMessagePath(terminationMessagePath)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withTerminationMessagePolicy

```ts
withTerminationMessagePolicy(terminationMessagePolicy)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withTty

```ts
withTty(tty)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withVolumeDevices

```ts
withVolumeDevices(volumeDevices)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withVolumeDevicesMixin

```ts
withVolumeDevicesMixin(volumeDevices)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.override.statefulSet.spec.template.spec.containers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.withWorkingDir

```ts
withWorkingDir(workingDir)
```



## obj spec.override.statefulSet.spec.template.spec.containers.env



### fn spec.override.statefulSet.spec.template.spec.containers.env.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.containers.env.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.containers.env.valueFrom



## obj spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.configMapKeyRef



### fn spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.fieldRef



### fn spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.resourceFieldRef



### fn spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.secretKeyRef



### fn spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.containers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.containers.envFrom



### fn spec.override.statefulSet.spec.template.spec.containers.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.override.statefulSet.spec.template.spec.containers.envFrom.configMapRef



### fn spec.override.statefulSet.spec.template.spec.containers.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.containers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.containers.envFrom.secretRef



### fn spec.override.statefulSet.spec.template.spec.containers.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.containers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.containers.lifecycle



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.withStopSignal

```ts
withStopSignal(stopSignal)
```



## obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart



## obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.exec



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.httpGet



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.sleep



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop



## obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.exec



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.httpGet



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.sleep



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.containers.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.containers.livenessProbe



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.override.statefulSet.spec.template.spec.containers.livenessProbe.exec



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.containers.livenessProbe.grpc



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.override.statefulSet.spec.template.spec.containers.livenessProbe.httpGet



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.containers.livenessProbe.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.containers.livenessProbe.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.containers.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.containers.ports



### fn spec.override.statefulSet.spec.template.spec.containers.ports.withContainerPort

```ts
withContainerPort(containerPort)
```



### fn spec.override.statefulSet.spec.template.spec.containers.ports.withHostIP

```ts
withHostIP(hostIP)
```



### fn spec.override.statefulSet.spec.template.spec.containers.ports.withHostPort

```ts
withHostPort(hostPort)
```



### fn spec.override.statefulSet.spec.template.spec.containers.ports.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.containers.ports.withProtocol

```ts
withProtocol(protocol)
```



## obj spec.override.statefulSet.spec.template.spec.containers.readinessProbe



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.override.statefulSet.spec.template.spec.containers.readinessProbe.exec



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.containers.readinessProbe.grpc



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.override.statefulSet.spec.template.spec.containers.readinessProbe.httpGet



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.containers.readinessProbe.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.containers.readinessProbe.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.containers.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.containers.resizePolicy



### fn spec.override.statefulSet.spec.template.spec.containers.resizePolicy.withResourceName

```ts
withResourceName(resourceName)
```



### fn spec.override.statefulSet.spec.template.spec.containers.resizePolicy.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



## obj spec.override.statefulSet.spec.template.spec.containers.resources



### fn spec.override.statefulSet.spec.template.spec.containers.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.override.statefulSet.spec.template.spec.containers.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.override.statefulSet.spec.template.spec.containers.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.override.statefulSet.spec.template.spec.containers.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.containers.resources.claims



### fn spec.override.statefulSet.spec.template.spec.containers.resources.claims.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.containers.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.override.statefulSet.spec.template.spec.containers.securityContext



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.override.statefulSet.spec.template.spec.containers.securityContext.appArmorProfile



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.override.statefulSet.spec.template.spec.containers.securityContext.capabilities



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.containers.securityContext.seLinuxOptions



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.override.statefulSet.spec.template.spec.containers.securityContext.seccompProfile



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.override.statefulSet.spec.template.spec.containers.securityContext.windowsOptions



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.override.statefulSet.spec.template.spec.containers.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.override.statefulSet.spec.template.spec.containers.startupProbe



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.override.statefulSet.spec.template.spec.containers.startupProbe.exec



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.containers.startupProbe.grpc



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.grpc.withService

```ts
withService(service)
```



## obj spec.override.statefulSet.spec.template.spec.containers.startupProbe.httpGet



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.containers.startupProbe.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.containers.startupProbe.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.containers.startupProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.containers.volumeDevices



### fn spec.override.statefulSet.spec.template.spec.containers.volumeDevices.withDevicePath

```ts
withDevicePath(devicePath)
```



### fn spec.override.statefulSet.spec.template.spec.containers.volumeDevices.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.containers.volumeMounts



### fn spec.override.statefulSet.spec.template.spec.containers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.override.statefulSet.spec.template.spec.containers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.override.statefulSet.spec.template.spec.containers.volumeMounts.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.containers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.containers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.override.statefulSet.spec.template.spec.containers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.override.statefulSet.spec.template.spec.containers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



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

## obj spec.override.statefulSet.spec.template.spec.dnsConfig.options



### fn spec.override.statefulSet.spec.template.spec.dnsConfig.options.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.dnsConfig.options.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withArgs

```ts
withArgs(args)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withEnv

```ts
withEnv(env)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withImage

```ts
withImage(image)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withPorts

```ts
withPorts(ports)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withPortsMixin

```ts
withPortsMixin(ports)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withResizePolicy

```ts
withResizePolicy(resizePolicy)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withResizePolicyMixin

```ts
withResizePolicyMixin(resizePolicy)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withStdin

```ts
withStdin(stdin)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withStdinOnce

```ts
withStdinOnce(stdinOnce)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withTargetContainerName

```ts
withTargetContainerName(targetContainerName)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withTerminationMessagePath

```ts
withTerminationMessagePath(terminationMessagePath)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withTerminationMessagePolicy

```ts
withTerminationMessagePolicy(terminationMessagePolicy)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withTty

```ts
withTty(tty)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withVolumeDevices

```ts
withVolumeDevices(volumeDevices)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withVolumeDevicesMixin

```ts
withVolumeDevicesMixin(volumeDevices)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.withWorkingDir

```ts
withWorkingDir(workingDir)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.env



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.configMapKeyRef



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.fieldRef



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.resourceFieldRef



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.secretKeyRef



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.envFrom



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.envFrom.configMapRef



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.envFrom.secretRef



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.withStopSignal

```ts
withStopSignal(stopSignal)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.exec



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.httpGet



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.sleep



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.exec



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.httpGet



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.sleep



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.exec



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.grpc



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.httpGet



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.ports



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.ports.withContainerPort

```ts
withContainerPort(containerPort)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.ports.withHostIP

```ts
withHostIP(hostIP)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.ports.withHostPort

```ts
withHostPort(hostPort)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.ports.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.ports.withProtocol

```ts
withProtocol(protocol)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.exec



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.grpc



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.httpGet



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.resizePolicy



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.resizePolicy.withResourceName

```ts
withResourceName(resourceName)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.resizePolicy.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.resources



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.resources.claims



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.resources.claims.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.appArmorProfile



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.capabilities



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.seLinuxOptions



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.seccompProfile



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.windowsOptions



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.exec



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.grpc



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.grpc.withService

```ts
withService(service)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.httpGet



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.startupProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.volumeDevices



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.volumeDevices.withDevicePath

```ts
withDevicePath(devicePath)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.volumeDevices.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.ephemeralContainers.volumeMounts



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.volumeMounts.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.override.statefulSet.spec.template.spec.ephemeralContainers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.override.statefulSet.spec.template.spec.hostAliases



### fn spec.override.statefulSet.spec.template.spec.hostAliases.withHostnames

```ts
withHostnames(hostnames)
```



### fn spec.override.statefulSet.spec.template.spec.hostAliases.withHostnamesMixin

```ts
withHostnamesMixin(hostnames)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.hostAliases.withIp

```ts
withIp(ip)
```



## obj spec.override.statefulSet.spec.template.spec.imagePullSecrets



### fn spec.override.statefulSet.spec.template.spec.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers



### fn spec.override.statefulSet.spec.template.spec.initContainers.withArgs

```ts
withArgs(args)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.withEnv

```ts
withEnv(env)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.withImage

```ts
withImage(image)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withPorts

```ts
withPorts(ports)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withPortsMixin

```ts
withPortsMixin(ports)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.withResizePolicy

```ts
withResizePolicy(resizePolicy)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withResizePolicyMixin

```ts
withResizePolicyMixin(resizePolicy)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withStdin

```ts
withStdin(stdin)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withStdinOnce

```ts
withStdinOnce(stdinOnce)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withTerminationMessagePath

```ts
withTerminationMessagePath(terminationMessagePath)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withTerminationMessagePolicy

```ts
withTerminationMessagePolicy(terminationMessagePolicy)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withTty

```ts
withTty(tty)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withVolumeDevices

```ts
withVolumeDevices(volumeDevices)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withVolumeDevicesMixin

```ts
withVolumeDevicesMixin(volumeDevices)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.withWorkingDir

```ts
withWorkingDir(workingDir)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.env



### fn spec.override.statefulSet.spec.template.spec.initContainers.env.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.env.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom



## obj spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.configMapKeyRef



### fn spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.fieldRef



### fn spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.resourceFieldRef



### fn spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.secretKeyRef



### fn spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.envFrom



### fn spec.override.statefulSet.spec.template.spec.initContainers.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.envFrom.configMapRef



### fn spec.override.statefulSet.spec.template.spec.initContainers.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.envFrom.secretRef



### fn spec.override.statefulSet.spec.template.spec.initContainers.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.withStopSignal

```ts
withStopSignal(stopSignal)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart



## obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.exec



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.httpGet



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.sleep



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop



## obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.exec



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.httpGet



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.sleep



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.exec



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.grpc



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.httpGet



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.ports



### fn spec.override.statefulSet.spec.template.spec.initContainers.ports.withContainerPort

```ts
withContainerPort(containerPort)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.ports.withHostIP

```ts
withHostIP(hostIP)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.ports.withHostPort

```ts
withHostPort(hostPort)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.ports.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.ports.withProtocol

```ts
withProtocol(protocol)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.exec



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.grpc



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.httpGet



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.resizePolicy



### fn spec.override.statefulSet.spec.template.spec.initContainers.resizePolicy.withResourceName

```ts
withResourceName(resourceName)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.resizePolicy.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.resources



### fn spec.override.statefulSet.spec.template.spec.initContainers.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.initContainers.resources.claims



### fn spec.override.statefulSet.spec.template.spec.initContainers.resources.claims.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.securityContext



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.securityContext.appArmorProfile



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.securityContext.capabilities



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.initContainers.securityContext.seLinuxOptions



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.securityContext.seccompProfile



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.securityContext.windowsOptions



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.startupProbe



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.exec



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.grpc



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.grpc.withService

```ts
withService(service)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.httpGet



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.httpGet.httpHeaders



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.tcpSocket



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.startupProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.volumeDevices



### fn spec.override.statefulSet.spec.template.spec.initContainers.volumeDevices.withDevicePath

```ts
withDevicePath(devicePath)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.volumeDevices.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.initContainers.volumeMounts



### fn spec.override.statefulSet.spec.template.spec.initContainers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.volumeMounts.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.override.statefulSet.spec.template.spec.initContainers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.override.statefulSet.spec.template.spec.os



### fn spec.override.statefulSet.spec.template.spec.os.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.readinessGates



### fn spec.override.statefulSet.spec.template.spec.readinessGates.withConditionType

```ts
withConditionType(conditionType)
```



## obj spec.override.statefulSet.spec.template.spec.resourceClaims



### fn spec.override.statefulSet.spec.template.spec.resourceClaims.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.resourceClaims.withResourceClaimName

```ts
withResourceClaimName(resourceClaimName)
```



### fn spec.override.statefulSet.spec.template.spec.resourceClaims.withResourceClaimTemplateName

```ts
withResourceClaimTemplateName(resourceClaimTemplateName)
```



## obj spec.override.statefulSet.spec.template.spec.resources



### fn spec.override.statefulSet.spec.template.spec.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.override.statefulSet.spec.template.spec.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.override.statefulSet.spec.template.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.override.statefulSet.spec.template.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.resources.claims



### fn spec.override.statefulSet.spec.template.spec.resources.claims.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.override.statefulSet.spec.template.spec.schedulingGates



### fn spec.override.statefulSet.spec.template.spec.schedulingGates.withName

```ts
withName(name)
```



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



### fn spec.override.statefulSet.spec.template.spec.securityContext.withSeLinuxChangePolicy

```ts
withSeLinuxChangePolicy(seLinuxChangePolicy)
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

### fn spec.override.statefulSet.spec.template.spec.securityContext.withSupplementalGroupsPolicy

```ts
withSupplementalGroupsPolicy(supplementalGroupsPolicy)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.withSysctls

```ts
withSysctls(sysctls)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.withSysctlsMixin

```ts
withSysctlsMixin(sysctls)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.securityContext.appArmorProfile



### fn spec.override.statefulSet.spec.template.spec.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.appArmorProfile.withType

```ts
withType(type)
```



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



## obj spec.override.statefulSet.spec.template.spec.securityContext.sysctls



### fn spec.override.statefulSet.spec.template.spec.securityContext.sysctls.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.sysctls.withValue

```ts
withValue(value)
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



### fn spec.override.statefulSet.spec.template.spec.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.override.statefulSet.spec.template.spec.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.override.statefulSet.spec.template.spec.tolerations



### fn spec.override.statefulSet.spec.template.spec.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.override.statefulSet.spec.template.spec.tolerations.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.tolerations.withValue

```ts
withValue(value)
```



## obj spec.override.statefulSet.spec.template.spec.topologySpreadConstraints



### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.withMaxSkew

```ts
withMaxSkew(maxSkew)
```



### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.withMinDomains

```ts
withMinDomains(minDomains)
```



### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.withNodeAffinityPolicy

```ts
withNodeAffinityPolicy(nodeAffinityPolicy)
```



### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.withNodeTaintsPolicy

```ts
withNodeTaintsPolicy(nodeTaintsPolicy)
```



### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.withWhenUnsatisfiable

```ts
withWhenUnsatisfiable(whenUnsatisfiable)
```



## obj spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.labelSelector



### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.labelSelector.matchExpressions



### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.topologySpreadConstraints.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.volumes



### fn spec.override.statefulSet.spec.template.spec.volumes.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.awsElasticBlockStore



### fn spec.override.statefulSet.spec.template.spec.volumes.awsElasticBlockStore.withFsType

```ts
withFsType(fsType)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.awsElasticBlockStore.withPartition

```ts
withPartition(partition)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.awsElasticBlockStore.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.awsElasticBlockStore.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.azureDisk



### fn spec.override.statefulSet.spec.template.spec.volumes.azureDisk.withCachingMode

```ts
withCachingMode(cachingMode)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.azureDisk.withDiskName

```ts
withDiskName(diskName)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.azureDisk.withDiskURI

```ts
withDiskURI(diskURI)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.azureDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.azureDisk.withKind

```ts
withKind(kind)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.azureDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.azureFile



### fn spec.override.statefulSet.spec.template.spec.volumes.azureFile.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.azureFile.withSecretName

```ts
withSecretName(secretName)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.azureFile.withShareName

```ts
withShareName(shareName)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.cephfs



### fn spec.override.statefulSet.spec.template.spec.volumes.cephfs.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.cephfs.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.volumes.cephfs.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.cephfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.cephfs.withSecretFile

```ts
withSecretFile(secretFile)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.cephfs.withUser

```ts
withUser(user)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.cephfs.secretRef



### fn spec.override.statefulSet.spec.template.spec.volumes.cephfs.secretRef.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.cinder



### fn spec.override.statefulSet.spec.template.spec.volumes.cinder.withFsType

```ts
withFsType(fsType)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.cinder.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.cinder.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.cinder.secretRef



### fn spec.override.statefulSet.spec.template.spec.volumes.cinder.secretRef.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.configMap



### fn spec.override.statefulSet.spec.template.spec.volumes.configMap.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.configMap.withItems

```ts
withItems(items)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.volumes.configMap.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.configMap.items



### fn spec.override.statefulSet.spec.template.spec.volumes.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.csi



### fn spec.override.statefulSet.spec.template.spec.volumes.csi.withDriver

```ts
withDriver(driver)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.csi.withFsType

```ts
withFsType(fsType)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.csi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.csi.withVolumeAttributes

```ts
withVolumeAttributes(volumeAttributes)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.csi.withVolumeAttributesMixin

```ts
withVolumeAttributesMixin(volumeAttributes)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.volumes.csi.nodePublishSecretRef



### fn spec.override.statefulSet.spec.template.spec.volumes.csi.nodePublishSecretRef.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.downwardAPI



### fn spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.items



### fn spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.items.fieldRef



### fn spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.items.resourceFieldRef



### fn spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.emptyDir



### fn spec.override.statefulSet.spec.template.spec.volumes.emptyDir.withMedium

```ts
withMedium(medium)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.emptyDir.withSizeLimit

```ts
withSizeLimit(sizeLimit)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral



## obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.withMetadata

```ts
withMetadata(metadata)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.withMetadataMixin

```ts
withMetadataMixin(metadata)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModes

```ts
withAccessModes(accessModes)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModesMixin

```ts
withAccessModesMixin(accessModes)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.withStorageClassName

```ts
withStorageClassName(storageClassName)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeAttributesClassName

```ts
withVolumeAttributesClassName(volumeAttributesClassName)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeMode

```ts
withVolumeMode(volumeMode)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withKind

```ts
withKind(kind)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withKind

```ts
withKind(kind)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.volumes.fc



### fn spec.override.statefulSet.spec.template.spec.volumes.fc.withFsType

```ts
withFsType(fsType)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.fc.withLun

```ts
withLun(lun)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.fc.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.fc.withTargetWWNs

```ts
withTargetWWNs(targetWWNs)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.fc.withTargetWWNsMixin

```ts
withTargetWWNsMixin(targetWWNs)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.volumes.fc.withWwids

```ts
withWwids(wwids)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.fc.withWwidsMixin

```ts
withWwidsMixin(wwids)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.volumes.flexVolume



### fn spec.override.statefulSet.spec.template.spec.volumes.flexVolume.withDriver

```ts
withDriver(driver)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.flexVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.flexVolume.withOptions

```ts
withOptions(options)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.flexVolume.withOptionsMixin

```ts
withOptionsMixin(options)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.volumes.flexVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.flexVolume.secretRef



### fn spec.override.statefulSet.spec.template.spec.volumes.flexVolume.secretRef.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.flocker



### fn spec.override.statefulSet.spec.template.spec.volumes.flocker.withDatasetName

```ts
withDatasetName(datasetName)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.flocker.withDatasetUUID

```ts
withDatasetUUID(datasetUUID)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.gcePersistentDisk



### fn spec.override.statefulSet.spec.template.spec.volumes.gcePersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.gcePersistentDisk.withPartition

```ts
withPartition(partition)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.gcePersistentDisk.withPdName

```ts
withPdName(pdName)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.gcePersistentDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.gitRepo



### fn spec.override.statefulSet.spec.template.spec.volumes.gitRepo.withDirectory

```ts
withDirectory(directory)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.gitRepo.withRepository

```ts
withRepository(repository)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.gitRepo.withRevision

```ts
withRevision(revision)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.glusterfs



### fn spec.override.statefulSet.spec.template.spec.volumes.glusterfs.withEndpoints

```ts
withEndpoints(endpoints)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.glusterfs.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.glusterfs.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.hostPath



### fn spec.override.statefulSet.spec.template.spec.volumes.hostPath.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.hostPath.withType

```ts
withType(type)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.image



### fn spec.override.statefulSet.spec.template.spec.volumes.image.withPullPolicy

```ts
withPullPolicy(pullPolicy)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.image.withReference

```ts
withReference(reference)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.iscsi



### fn spec.override.statefulSet.spec.template.spec.volumes.iscsi.withChapAuthDiscovery

```ts
withChapAuthDiscovery(chapAuthDiscovery)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.iscsi.withChapAuthSession

```ts
withChapAuthSession(chapAuthSession)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.iscsi.withFsType

```ts
withFsType(fsType)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.iscsi.withInitiatorName

```ts
withInitiatorName(initiatorName)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.iscsi.withIqn

```ts
withIqn(iqn)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.iscsi.withIscsiInterface

```ts
withIscsiInterface(iscsiInterface)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.iscsi.withLun

```ts
withLun(lun)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.iscsi.withPortals

```ts
withPortals(portals)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.iscsi.withPortalsMixin

```ts
withPortalsMixin(portals)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.volumes.iscsi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.iscsi.withTargetPortal

```ts
withTargetPortal(targetPortal)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.iscsi.secretRef



### fn spec.override.statefulSet.spec.template.spec.volumes.iscsi.secretRef.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.nfs



### fn spec.override.statefulSet.spec.template.spec.volumes.nfs.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.nfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.nfs.withServer

```ts
withServer(server)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.persistentVolumeClaim



### fn spec.override.statefulSet.spec.template.spec.volumes.persistentVolumeClaim.withClaimName

```ts
withClaimName(claimName)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.persistentVolumeClaim.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.photonPersistentDisk



### fn spec.override.statefulSet.spec.template.spec.volumes.photonPersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.photonPersistentDisk.withPdID

```ts
withPdID(pdID)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.portworxVolume



### fn spec.override.statefulSet.spec.template.spec.volumes.portworxVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.portworxVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.portworxVolume.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.projected



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.withSources

```ts
withSources(sources)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.withSourcesMixin

```ts
withSourcesMixin(sources)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources



## obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.withOptional

```ts
withOptional(optional)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.withPath

```ts
withPath(path)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.withSignerName

```ts
withSignerName(signerName)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.configMap



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.configMap.withItems

```ts
withItems(items)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.configMap.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.configMap.items



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.items



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.items.fieldRef



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.secret



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.secret.withItems

```ts
withItems(items)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.secret.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.secret.withOptional

```ts
withOptional(optional)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.secret.items



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.secret.items.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.secret.items.withPath

```ts
withPath(path)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.projected.sources.serviceAccountToken



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.serviceAccountToken.withAudience

```ts
withAudience(audience)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.serviceAccountToken.withExpirationSeconds

```ts
withExpirationSeconds(expirationSeconds)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.projected.sources.serviceAccountToken.withPath

```ts
withPath(path)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.quobyte



### fn spec.override.statefulSet.spec.template.spec.volumes.quobyte.withGroup

```ts
withGroup(group)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.quobyte.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.quobyte.withRegistry

```ts
withRegistry(registry)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.quobyte.withTenant

```ts
withTenant(tenant)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.quobyte.withUser

```ts
withUser(user)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.quobyte.withVolume

```ts
withVolume(volume)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.rbd



### fn spec.override.statefulSet.spec.template.spec.volumes.rbd.withFsType

```ts
withFsType(fsType)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.rbd.withImage

```ts
withImage(image)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.rbd.withKeyring

```ts
withKeyring(keyring)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.rbd.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.rbd.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.volumes.rbd.withPool

```ts
withPool(pool)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.rbd.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.rbd.withUser

```ts
withUser(user)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.rbd.secretRef



### fn spec.override.statefulSet.spec.template.spec.volumes.rbd.secretRef.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.scaleIO



### fn spec.override.statefulSet.spec.template.spec.volumes.scaleIO.withFsType

```ts
withFsType(fsType)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.scaleIO.withGateway

```ts
withGateway(gateway)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.scaleIO.withProtectionDomain

```ts
withProtectionDomain(protectionDomain)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.scaleIO.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.scaleIO.withSslEnabled

```ts
withSslEnabled(sslEnabled)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.scaleIO.withStorageMode

```ts
withStorageMode(storageMode)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.scaleIO.withStoragePool

```ts
withStoragePool(storagePool)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.scaleIO.withSystem

```ts
withSystem(system)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.scaleIO.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.scaleIO.secretRef



### fn spec.override.statefulSet.spec.template.spec.volumes.scaleIO.secretRef.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.secret



### fn spec.override.statefulSet.spec.template.spec.volumes.secret.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.secret.withItems

```ts
withItems(items)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.template.spec.volumes.secret.withOptional

```ts
withOptional(optional)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.secret.withSecretName

```ts
withSecretName(secretName)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.secret.items



### fn spec.override.statefulSet.spec.template.spec.volumes.secret.items.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.secret.items.withPath

```ts
withPath(path)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.storageos



### fn spec.override.statefulSet.spec.template.spec.volumes.storageos.withFsType

```ts
withFsType(fsType)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.storageos.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.storageos.withVolumeName

```ts
withVolumeName(volumeName)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.storageos.withVolumeNamespace

```ts
withVolumeNamespace(volumeNamespace)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.storageos.secretRef



### fn spec.override.statefulSet.spec.template.spec.volumes.storageos.secretRef.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.template.spec.volumes.vsphereVolume



### fn spec.override.statefulSet.spec.template.spec.volumes.vsphereVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.vsphereVolume.withStoragePolicyID

```ts
withStoragePolicyID(storagePolicyID)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.vsphereVolume.withStoragePolicyName

```ts
withStoragePolicyName(storagePolicyName)
```



### fn spec.override.statefulSet.spec.template.spec.volumes.vsphereVolume.withVolumePath

```ts
withVolumePath(volumePath)
```



## obj spec.override.statefulSet.spec.updateStrategy



### fn spec.override.statefulSet.spec.updateStrategy.withType

```ts
withType(type)
```



## obj spec.override.statefulSet.spec.updateStrategy.rollingUpdate



### fn spec.override.statefulSet.spec.updateStrategy.rollingUpdate.withMaxUnavailable

```ts
withMaxUnavailable(maxUnavailable)
```



### fn spec.override.statefulSet.spec.updateStrategy.rollingUpdate.withPartition

```ts
withPartition(partition)
```



## obj spec.override.statefulSet.spec.volumeClaimTemplates



### fn spec.override.statefulSet.spec.volumeClaimTemplates.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.withKind

```ts
withKind(kind)
```



## obj spec.override.statefulSet.spec.volumeClaimTemplates.metadata



### fn spec.override.statefulSet.spec.volumeClaimTemplates.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.volumeClaimTemplates.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.volumeClaimTemplates.metadata.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.metadata.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.override.statefulSet.spec.volumeClaimTemplates.spec



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.withAccessModes

```ts
withAccessModes(accessModes)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.withAccessModesMixin

```ts
withAccessModesMixin(accessModes)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.withStorageClassName

```ts
withStorageClassName(storageClassName)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.withVolumeAttributesClassName

```ts
withVolumeAttributesClassName(volumeAttributesClassName)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.withVolumeMode

```ts
withVolumeMode(volumeMode)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.override.statefulSet.spec.volumeClaimTemplates.spec.dataSource



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.dataSource.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.dataSource.withKind

```ts
withKind(kind)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.dataSource.withName

```ts
withName(name)
```



## obj spec.override.statefulSet.spec.volumeClaimTemplates.spec.dataSourceRef



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.dataSourceRef.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.dataSourceRef.withKind

```ts
withKind(kind)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.dataSourceRef.withName

```ts
withName(name)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.dataSourceRef.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.override.statefulSet.spec.volumeClaimTemplates.spec.resources



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.volumeClaimTemplates.spec.selector



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.override.statefulSet.spec.volumeClaimTemplates.spec.selector.matchExpressions



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.selector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.selector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.override.statefulSet.spec.volumeClaimTemplates.spec.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.persistence

"The desired persistent storage configuration for each Pod in the cluster."

### fn spec.persistence.withStorage

```ts
withStorage(storage)
```

"The requested size of the persistent volume attached to each Pod in the RabbitmqCluster.\nThe format of this field matches that defined by kubernetes/apimachinery.\nSee https://pkg.go.dev/k8s.io/apimachinery/pkg/api/resource#Quantity for more info on the format of this field."

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

"Modify to add to the rabbitmq.conf file in addition to default configurations set by the operator.\nModifying this property on an existing RabbitmqCluster will trigger a StatefulSet rolling restart and will cause rabbitmq downtime.\nFor more information on this config, see https://www.rabbitmq.com/configure.html#config-file"

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

"Specify any rabbitmq advanced.config configurations to apply to the cluster.\nFor more information on advanced config, see https://www.rabbitmq.com/configure.html#advanced-config-file"

### fn spec.rabbitmq.withEnvConfig

```ts
withEnvConfig(envConfig)
```

"Modify to add to the rabbitmq-env.conf file. Modifying this property on an existing RabbitmqCluster will trigger a StatefulSet rolling restart and will cause rabbitmq downtime.\nFor more information on env config, see https://www.rabbitmq.com/man/rabbitmq-env.conf.5.html"

### fn spec.rabbitmq.withErlangInetConfig

```ts
withErlangInetConfig(erlangInetConfig)
```

"Erlang Inet configuration to apply to the Erlang VM running rabbit.\nSee also: https://www.erlang.org/doc/apps/erts/inet_cfg.html"

## obj spec.resources

"The desired compute resource requirements of Pods in the cluster."

### fn spec.resources.withClaims

```ts
withClaims(claims)
```

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis is an alpha field and requires enabling the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

### fn spec.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis is an alpha field and requires enabling the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

**Note:** This function appends passed data to existing values

### fn spec.resources.withLimits

```ts
withLimits(limits)
```

"Limits describes the maximum amount of compute resources allowed.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

### fn spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```

"Limits describes the maximum amount of compute resources allowed.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

**Note:** This function appends passed data to existing values

### fn spec.resources.withRequests

```ts
withRequests(requests)
```

"Requests describes the minimum amount of compute resources required.\nIf Requests is omitted for a container, it defaults to Limits if that is explicitly specified,\notherwise to an implementation-defined value. Requests cannot exceed Limits.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

### fn spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```

"Requests describes the minimum amount of compute resources required.\nIf Requests is omitted for a container, it defaults to Limits if that is explicitly specified,\notherwise to an implementation-defined value. Requests cannot exceed Limits.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

**Note:** This function appends passed data to existing values

## obj spec.resources.claims

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis is an alpha field and requires enabling the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

### fn spec.resources.claims.withName

```ts
withName(name)
```

"Name must match the name of one entry in pod.spec.resourceClaims of\nthe Pod where this field is used. It makes that resource available\ninside a container."

### fn spec.resources.claims.withRequest

```ts
withRequest(request)
```

"Request is the name chosen for a request in the referenced claim.\nIf empty, everything from the claim is made available, otherwise\nonly the result of this request."

## obj spec.secretBackend

"Secret backend configuration for the RabbitmqCluster.\nEnables to fetch default user credentials and certificates from K8s external secret stores."

## obj spec.secretBackend.externalSecret

"LocalObjectReference contains enough information to let you locate the\nreferenced object inside the same namespace."

### fn spec.secretBackend.externalSecret.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.secretBackend.vault

"VaultSpec will add Vault annotations (see https://www.vaultproject.io/docs/platform/k8s/injector/annotations)\nto RabbitMQ Pods. It requires a Vault Agent Sidecar Injector (https://www.vaultproject.io/docs/platform/k8s/injector)\nto be installed in the K8s cluster. The injector is a K8s Mutation Webhook Controller that alters RabbitMQ Pod specifications\n(based on the added Vault annotations) to include Vault Agent containers that render Vault secrets to the volume."

### fn spec.secretBackend.vault.withAnnotations

```ts
withAnnotations(annotations)
```

"Vault annotations that override the Vault annotations set by the cluster-operator.\nFor a list of valid Vault annotations, see https://www.vaultproject.io/docs/platform/k8s/injector/annotations"

### fn spec.secretBackend.vault.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Vault annotations that override the Vault annotations set by the cluster-operator.\nFor a list of valid Vault annotations, see https://www.vaultproject.io/docs/platform/k8s/injector/annotations"

**Note:** This function appends passed data to existing values

### fn spec.secretBackend.vault.withDefaultUserPath

```ts
withDefaultUserPath(defaultUserPath)
```

"Path in Vault to access a KV (Key-Value) secret with the fields username and password for the default user.\nFor example \"secret/data/rabbitmq/config\"."

### fn spec.secretBackend.vault.withDefaultUserUpdaterImage

```ts
withDefaultUserUpdaterImage(defaultUserUpdaterImage)
```

"Sidecar container that updates the default user's password in RabbitMQ when it changes in Vault.\nAdditionally, it updates /var/lib/rabbitmq/.rabbitmqadmin.conf (used by rabbitmqadmin CLI).\nSet to empty string to disable the sidecar container."

### fn spec.secretBackend.vault.withRole

```ts
withRole(role)
```

"Role in Vault.\nIf vault.defaultUserPath is set, this role must have capability to read the pre-created default user credential in Vault.\nIf vault.tls is set, this role must have capability to create and update certificates in the Vault PKI engine for the domains\n\"<namespace>\" and \"<namespace>.svc\"."

## obj spec.secretBackend.vault.tls



### fn spec.secretBackend.vault.tls.withAltNames

```ts
withAltNames(altNames)
```

"Specifies the requested Subject Alternative Names (SANs), in a comma-delimited list.\nThese will be appended to the SANs added by the cluster-operator.\nThe cluster-operator will add SANs:\n\"<RabbitmqCluster name>-server-<index>.<RabbitmqCluster name>-nodes.<namespace>\" for each pod,\ne.g. \"myrabbit-server-0.myrabbit-nodes.default\"."

### fn spec.secretBackend.vault.tls.withCommonName

```ts
withCommonName(commonName)
```

"Specifies the requested certificate Common Name (CN).\nDefaults to <serviceName>.<namespace>.svc if not provided."

### fn spec.secretBackend.vault.tls.withIpSans

```ts
withIpSans(ipSans)
```

"Specifies the requested IP Subject Alternative Names, in a comma-delimited list."

### fn spec.secretBackend.vault.tls.withPkiIssuerPath

```ts
withPkiIssuerPath(pkiIssuerPath)
```

"Path in Vault PKI engine.\nFor example \"pki/issue/hashicorp-com\".\nrequired"

### fn spec.secretBackend.vault.tls.withPkiRootPath

```ts
withPkiRootPath(pkiRootPath)
```

"Specifies an optional path to retrieve the root CA from vault.  Useful if certificates are issued by an intermediate CA"

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

### fn spec.service.withIpFamilyPolicy

```ts
withIpFamilyPolicy(ipFamilyPolicy)
```

"IPFamilyPolicy represents the dual-stack-ness requested or required by a Service\nSee also: https://pkg.go.dev/k8s.io/api/core/v1#IPFamilyPolicy"

### fn spec.service.withLabels

```ts
withLabels(labels)
```



### fn spec.service.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.service.withType

```ts
withType(type)
```

"Type of Service to create for the cluster. Must be one of: ClusterIP, LoadBalancer, NodePort.\nFor more info see https://pkg.go.dev/k8s.io/api/core/v1#ServiceType"

## obj spec.tls

"TLS-related configuration for the RabbitMQ cluster."

### fn spec.tls.withCaSecretName

```ts
withCaSecretName(caSecretName)
```

"Name of a Secret in the same Namespace as the RabbitmqCluster, containing the Certificate Authority's public certificate for TLS.\nThe Secret must store this as ca.crt.\nThis Secret can be created by running `kubectl create secret generic ca-secret --from-file=ca.crt=path/to/ca.crt`\nUsed for mTLS, and TLS for rabbitmq_web_stomp and rabbitmq_web_mqtt."

### fn spec.tls.withDisableNonTLSListeners

```ts
withDisableNonTLSListeners(disableNonTLSListeners)
```

"When set to true, the RabbitmqCluster disables non-TLS listeners for RabbitMQ, management plugin and for any enabled plugins in the following list: stomp, mqtt, web_stomp, web_mqtt.\nOnly TLS-enabled clients will be able to connect."

### fn spec.tls.withSecretName

```ts
withSecretName(secretName)
```

"Name of a Secret in the same Namespace as the RabbitmqCluster, containing the server's private key & public certificate for TLS.\nThe Secret must store these as tls.key and tls.crt, respectively.\nThis Secret can be created by running `kubectl create secret tls tls-secret --cert=path/to/tls.crt --key=path/to/tls.key`"

## obj spec.tolerations

"Tolerations is the list of Toleration resources attached to each Pod in the RabbitmqCluster."

### fn spec.tolerations.withEffect

```ts
withEffect(effect)
```

"Effect indicates the taint effect to match. Empty means match all taint effects.\nWhen specified, allowed values are NoSchedule, PreferNoSchedule and NoExecute."

### fn spec.tolerations.withKey

```ts
withKey(key)
```

"Key is the taint key that the toleration applies to. Empty means match all taint keys.\nIf the key is empty, operator must be Exists; this combination means to match all values and all keys."

### fn spec.tolerations.withOperator

```ts
withOperator(operator)
```

"Operator represents a key's relationship to the value.\nValid operators are Exists and Equal. Defaults to Equal.\nExists is equivalent to wildcard for value, so that a pod can\ntolerate all taints of a particular category."

### fn spec.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```

"TolerationSeconds represents the period of time the toleration (which must be\nof effect NoExecute, otherwise this field is ignored) tolerates the taint. By default,\nit is not set, which means tolerate the taint forever (do not evict). Zero and\nnegative values will be treated as 0 (evict immediately) by the system."

### fn spec.tolerations.withValue

```ts
withValue(value)
```

"Value is the taint value the toleration matches to.\nIf the operator is Exists, the value should be empty, otherwise just a regular string."