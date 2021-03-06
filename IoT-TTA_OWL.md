<?xml version="1.0"?>
<rdf:RDF xmlns="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT/IIoT#"
     xml:base="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT/IIoT"
     xmlns:p="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/"
     xmlns:owl="http://www.w3.org/2002/07/owl#"
     xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
     xmlns:xml="http://www.w3.org/XML/1998/namespace"
     xmlns:xsd="http://www.w3.org/2001/XMLSchema#"
     xmlns:IIoT="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#"
     xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#"
     xmlns:swrl="http://www.w3.org/2003/11/swrl#"
     xmlns:swrla="http://swrl.stanford.edu/ontologies/3.3/swrla.owl#"
     xmlns:swrlb="http://www.w3.org/2003/11/swrlb#">
    <owl:Ontology rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT">
        <owl:versionIRI rdf:resource="urn:absolute:1.3."/>
    </owl:Ontology>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Annotation properties
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://swrl.stanford.edu/ontologies/3.3/swrla.owl#isRuleEnabled -->

    <owl:AnnotationProperty rdf:about="http://swrl.stanford.edu/ontologies/3.3/swrla.owl#isRuleEnabled"/>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Object Properties
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDealing_with_sensitive_data -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDealing_with_sensitive_data">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_solution"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDevelopEdgeSecurity -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDevelopEdgeSecurity">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_application"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLack_security_measure -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLack_security_measure">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_common_protocol"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_problem"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocols_were_layered -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocols_were_layered">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_common_protocol"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_today_protocol"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_hasCapability -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_hasCapability">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topObjectProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_capability"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport_communication -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport_communication">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_today_protocol"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_capability"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTauthentication -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTauthentication">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMQTT"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAsymmetric_public_keys"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTJSON_Web_Token"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTbest_Practices -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTbest_Practices">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_security"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_application"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTchallenge -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTchallenge">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_problem"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_security"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTcountermeasure -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTcountermeasure">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_problem"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_solution"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTdata_transfer -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTdata_transfer">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMQTT"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDevice"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasAlgorithm -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasAlgorithm">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGateway"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAnalytics"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_Mining"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMachine_Learning"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNeural_Network"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasCapability -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasCapability">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topObjectProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData_capability"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasConnection -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasConnection">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGateway"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasConnectionTo -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasConnectionTo">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPLC"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasElement -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasElement">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAndrew"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTransducer"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasFunctionality -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasFunctionality">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_center"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasLayer -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasLayer">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIIoTLayers"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCapabilities"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDevice"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNetwork"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasProblem -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasProblem">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_problem"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasSecurity_problem -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasSecurity_problem">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_security"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasService -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasService">
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#FunctionalProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_center"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasSolution -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasSolution">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_problem"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_security"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasTechnology -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasTechnology">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_application"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_technology"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasTool -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThasTool">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTechnology"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThas_SecuritySolution -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThas_SecuritySolution">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_security"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisApplied -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisApplied">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProgramming"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer_cluster"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_center"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisConnectedBy -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisConnectedBy">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProcessing_Board"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisControlledBy -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisControlledBy">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPurpose-built_Device"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTICS"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisHeated -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisHeated">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial_oven"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisIdentified -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisIdentified">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPassive_things"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBLE"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNFC_tag"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOptical_tag"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRFID_tag"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisIncluded -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisIncluded">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicrocontroller"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPurpose-built_Device"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisLayerOf -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisLayerOf">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCapabilities"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDevice"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNetwork"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIIoTLayers"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisManagedBy -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisManagedBy">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProgramming_Language"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWeb_Technology"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisPartOf -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisPartOf">
        <rdfs:subPropertyOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisIncluded"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPLC"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTICS"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisProcessed -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisProcessed">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData_capability"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisProviding -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisProviding">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProcessing_Board"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisRegisteredWith -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisRegisteredWith">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDigital_twin"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisRepresentationOf -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisRepresentationOf">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDigital_twin"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisSecurityFor -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisSecurityFor">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAndrew"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTICS"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisToolFor -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisToolFor">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTechnology"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisType -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisType">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPLC"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisUsedBy -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisUsedBy">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTechnology"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisUsedIn -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTisUsedIn">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMQTT"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHardware_Platform"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPurpose-built_Device"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTlogin -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTlogin">
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGateway"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTmanages -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTmanages">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGateway"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTpowerD0 -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTpowerD0">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_Photon"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTrequires -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTrequires">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData_app"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData_capability"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTsendMessage -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTsendMessage">
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_cloud"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTsupporting_tool -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTsupporting_tool">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topObjectProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_application"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTthreats_to_data_security -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTthreats_to_data_security">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topObjectProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_problem"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTuniformAccess -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTuniformAccess">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDevice"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTuseAlgorithm -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTuseAlgorithm">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topObjectProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_center"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTuseProgramming -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTuseProgramming">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topObjectProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProgramming"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTwire -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTwire">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_Photon"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFlow"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#flow_services -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#flow_services">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_Photon"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Subscriber"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#heat -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#heat">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRTD_sensor"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial_oven"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#read -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#read">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFlow"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Firmware"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#regulationTemperature -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#regulationTemperature">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRTD_sensor"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial_oven"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#request -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#request">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_cloud"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Subscriber"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#send -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#send">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Firmware"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_cloud"/>
    </owl:ObjectProperty>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Data properties
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAccuracy_RTD -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAccuracy_RTD">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRTD_sensor"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCPU -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCPU">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicrocontroller"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicroprocessor"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTD0_pin -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTD0_pin">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_Photon"/>
        <rdfs:domain>
            <owl:Class>
                <owl:unionOf rdf:parseType="Collection">
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTD0_pin"/>
                        <owl:hasValue>High</owl:hasValue>
                    </owl:Restriction>
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTD0_pin"/>
                        <owl:hasValue>Low</owl:hasValue>
                    </owl:Restriction>
                </owl:unionOf>
            </owl:Class>
        </rdfs:domain>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEEPROM -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEEPROM">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicrocontroller"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFireFly_nodes -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFireFly_nodes">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWireless_sensor_network"/>
        <rdfs:domain>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFireFly_nodes"/>
                <owl:someValuesFrom>
                    <rdfs:Datatype>
                        <owl:onDatatype rdf:resource="http://www.w3.org/2001/XMLSchema#integer"/>
                        <owl:withRestrictions rdf:parseType="Collection">
                            <rdf:Description>
                                <xsd:minInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">20</xsd:minInclusive>
                            </rdf:Description>
                            <rdf:Description>
                                <xsd:maxInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">32</xsd:maxInclusive>
                            </rdf:Description>
                        </owl:withRestrictions>
                    </rdfs:Datatype>
                </owl:someValuesFrom>
            </owl:Restriction>
        </rdfs:domain>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#integer"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTI_O -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTI_O">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicrocontroller"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicroprocessor"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLocationAgent -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLocationAgent">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAndrew"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicroSD_card -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicroSD_card">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberyy_Pi"/>
        <rdfs:domain>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicroSD_card"/>
                <owl:someValuesFrom>
                    <rdfs:Datatype>
                        <owl:onDatatype rdf:resource="http://www.w3.org/2001/XMLSchema#double"/>
                        <owl:withRestrictions rdf:parseType="Collection">
                            <rdf:Description>
                                <xsd:minInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#double">8.0</xsd:minInclusive>
                            </rdf:Description>
                        </owl:withRestrictions>
                    </rdfs:Datatype>
                </owl:someValuesFrom>
            </owl:Restriction>
        </rdfs:domain>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#double"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMotors -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMotors">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPLC"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNetwork_nodes -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNetwork_nodes"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPassword_mobile_node -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPassword_mobile_node">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWireless_sensor_network"/>
        <rdfs:domain>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPassword_mobile_node"/>
                <owl:hasValue>password</owl:hasValue>
            </owl:Restriction>
        </rdfs:domain>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPower_supply -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPower_supply">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberyy_Pi"/>
        <rdfs:domain>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPower_supply"/>
                <owl:someValuesFrom>
                    <rdfs:Datatype>
                        <owl:onDatatype rdf:resource="http://www.w3.org/2001/XMLSchema#float"/>
                        <owl:withRestrictions rdf:parseType="Collection">
                            <rdf:Description>
                                <xsd:minInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#float">3.0</xsd:minInclusive>
                            </rdf:Description>
                        </owl:withRestrictions>
                    </rdfs:Datatype>
                </owl:someValuesFrom>
            </owl:Restriction>
        </rdfs:domain>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#float"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRAM -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRAM">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberyy_Pi"/>
        <rdfs:domain>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRAM"/>
                <owl:someValuesFrom>
                    <rdfs:Datatype>
                        <owl:onDatatype rdf:resource="http://www.w3.org/2001/XMLSchema#integer"/>
                        <owl:withRestrictions rdf:parseType="Collection">
                            <rdf:Description>
                                <xsd:minInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">2</xsd:minInclusive>
                            </rdf:Description>
                        </owl:withRestrictions>
                    </rdfs:Datatype>
                </owl:someValuesFrom>
            </owl:Restriction>
        </rdfs:domain>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#integer"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTROM -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTROM">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicroprocessor"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensors -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensors">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPLC"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTemperature_range -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTemperature_range">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial_oven"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTimer -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTimer">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicrocontroller"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicroprocessor"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTValue_sent -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTValue_sent">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_Photon"/>
        <rdfs:domain>
            <owl:Class>
                <owl:unionOf rdf:parseType="Collection">
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTValue_sent"/>
                        <owl:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">0</owl:hasValue>
                    </owl:Restriction>
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTValue_sent"/>
                        <owl:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">1</owl:hasValue>
                    </owl:Restriction>
                </owl:unionOf>
            </owl:Class>
        </rdfs:domain>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#integer"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTValves -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTValves">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPLC"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTdisconnect_timeout -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTdisconnect_timeout">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWireless_sensor_network"/>
        <rdfs:domain>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTdisconnect_timeout"/>
                <owl:someValuesFrom>
                    <rdfs:Datatype>
                        <owl:onDatatype rdf:resource="http://www.w3.org/2001/XMLSchema#integer"/>
                        <owl:withRestrictions rdf:parseType="Collection">
                            <rdf:Description>
                                <xsd:maxInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">1</xsd:maxInclusive>
                            </rdf:Description>
                        </owl:withRestrictions>
                    </rdfs:Datatype>
                </owl:someValuesFrom>
            </owl:Restriction>
        </rdfs:domain>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#integer"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTlanguages_tools -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTlanguages_tools">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPLC"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberry_Pi"/>
        <rdfs:domain>
            <owl:Class>
                <owl:unionOf rdf:parseType="Collection">
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTlanguages_tools"/>
                        <owl:hasValue>C</owl:hasValue>
                    </owl:Restriction>
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTlanguages_tools"/>
                        <owl:hasValue>C++</owl:hasValue>
                    </owl:Restriction>
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTlanguages_tools"/>
                        <owl:hasValue>Cosm</owl:hasValue>
                    </owl:Restriction>
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTlanguages_tools"/>
                        <owl:hasValue>Ladder Logic</owl:hasValue>
                    </owl:Restriction>
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTlanguages_tools"/>
                        <owl:hasValue>Nimbits</owl:hasValue>
                    </owl:Restriction>
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTlanguages_tools"/>
                        <owl:hasValue>Python</owl:hasValue>
                    </owl:Restriction>
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTlanguages_tools"/>
                        <owl:hasValue>Wyliodrin Studio</owl:hasValue>
                    </owl:Restriction>
                </owl:unionOf>
            </owl:Class>
        </rdfs:domain>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTmax_temperature_RTD -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTmax_temperature_RTD"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTmin_temperature_RTD -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTmin_temperature_RTD">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRTD_sensor"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoToperating_system -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoToperating_system">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberry_Pi"/>
        <rdfs:domain>
            <owl:Class>
                <owl:unionOf rdf:parseType="Collection">
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoToperating_system"/>
                        <owl:hasValue>Android</owl:hasValue>
                    </owl:Restriction>
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoToperating_system"/>
                        <owl:hasValue>Linux</owl:hasValue>
                    </owl:Restriction>
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoToperating_system"/>
                        <owl:hasValue>Mac</owl:hasValue>
                    </owl:Restriction>
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoToperating_system"/>
                        <owl:hasValue>RaspberryPi</owl:hasValue>
                    </owl:Restriction>
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoToperating_system"/>
                        <owl:hasValue>Raspbian</owl:hasValue>
                    </owl:Restriction>
                    <owl:Restriction>
                        <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoToperating_system"/>
                        <owl:hasValue>Windows</owl:hasValue>
                    </owl:Restriction>
                </owl:unionOf>
            </owl:Class>
        </rdfs:domain>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#hasAccuracy -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#hasAccuracy">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRTD_sensor"/>
        <rdfs:domain>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#hasAccuracy"/>
                <owl:someValuesFrom>
                    <rdfs:Datatype>
                        <owl:onDatatype rdf:resource="http://www.w3.org/2001/XMLSchema#decimal"/>
                        <owl:withRestrictions rdf:parseType="Collection">
                            <rdf:Description>
                                <xsd:minInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#decimal">0.1</xsd:minInclusive>
                            </rdf:Description>
                            <rdf:Description>
                                <xsd:maxInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#decimal">1.0</xsd:maxInclusive>
                            </rdf:Description>
                        </owl:withRestrictions>
                    </rdfs:Datatype>
                </owl:someValuesFrom>
            </owl:Restriction>
        </rdfs:domain>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#decimal"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#hasTemperatureRange -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#hasTemperatureRange">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial_oven"/>
        <rdfs:domain>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#hasTemperatureRange"/>
                <owl:someValuesFrom>
                    <rdfs:Datatype>
                        <owl:onDatatype rdf:resource="http://www.w3.org/2001/XMLSchema#integer"/>
                        <owl:withRestrictions rdf:parseType="Collection">
                            <rdf:Description>
                                <xsd:minInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">500</xsd:minInclusive>
                            </rdf:Description>
                            <rdf:Description>
                                <xsd:maxInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">510</xsd:maxInclusive>
                            </rdf:Description>
                        </owl:withRestrictions>
                    </rdfs:Datatype>
                </owl:someValuesFrom>
            </owl:Restriction>
        </rdfs:domain>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#hasTimeLimit -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#hasTimeLimit">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Firmware"/>
        <rdfs:domain>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#hasTimeLimit"/>
                <owl:someValuesFrom>
                    <rdfs:Datatype>
                        <owl:onDatatype rdf:resource="http://www.w3.org/2001/XMLSchema#integer"/>
                        <owl:withRestrictions rdf:parseType="Collection">
                            <rdf:Description>
                                <xsd:minInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">29</xsd:minInclusive>
                            </rdf:Description>
                            <rdf:Description>
                                <xsd:maxInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">30</xsd:maxInclusive>
                            </rdf:Description>
                        </owl:withRestrictions>
                    </rdfs:Datatype>
                </owl:someValuesFrom>
            </owl:Restriction>
        </rdfs:domain>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#integer"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#hasValueConnection -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#hasValueConnection">
        <rdfs:subPropertyOf rdf:resource="http://www.w3.org/2002/07/owl#topDataProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFlow"/>
        <rdfs:domain>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#hasValueConnection"/>
                <owl:someValuesFrom>
                    <rdfs:Datatype>
                        <owl:onDatatype rdf:resource="http://www.w3.org/2001/XMLSchema#integer"/>
                        <owl:withRestrictions rdf:parseType="Collection">
                            <rdf:Description>
                                <xsd:minInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">0</xsd:minInclusive>
                            </rdf:Description>
                            <rdf:Description>
                                <xsd:maxInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">1</xsd:maxInclusive>
                            </rdf:Description>
                        </owl:withRestrictions>
                    </rdfs:Datatype>
                </owl:someValuesFrom>
            </owl:Restriction>
        </rdfs:domain>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#integer"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#provideHeat -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#provideHeat">
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#FunctionalProperty"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRTD_sensor"/>
        <rdfs:domain>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#provideHeat"/>
                <owl:someValuesFrom>
                    <rdfs:Datatype>
                        <owl:onDatatype rdf:resource="http://www.w3.org/2001/XMLSchema#double"/>
                        <owl:withRestrictions rdf:parseType="Collection">
                            <rdf:Description>
                                <xsd:minInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#double">-200.0</xsd:minInclusive>
                            </rdf:Description>
                            <rdf:Description>
                                <xsd:maxInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#double">600.0</xsd:maxInclusive>
                            </rdf:Description>
                        </owl:withRestrictions>
                    </rdfs:Datatype>
                </owl:someValuesFrom>
            </owl:Restriction>
        </rdfs:domain>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#3V3_pin -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#3V3_pin">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_Photon"/>
    </owl:DatatypeProperty>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Classes
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAdaFruit -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAdaFruit">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMQTT_streams"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAdapter -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAdapter">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGateway"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAgriculture -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAgriculture">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAlgorithm -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAlgorithm">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLogic"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAnalytics -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAnalytics">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAlgorithm"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAndrew -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAndrew">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIIoTLayers"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTArduino -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTArduino">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicrocontroller"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAsymmetric_public_keys -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAsymmetric_public_keys">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCryptographic_system"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBLE -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBLE">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTechnology"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData_app -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData_app">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData_capability -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData_capability">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTechnology"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_facilities -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_facilities">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_problem -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_problem">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_security -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_security">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTC -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTC">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProgramming_Language"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCapabilities -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCapabilities">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIIoTLayers"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCloud_service -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCloud_service">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCloud_system -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCloud_system">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCloudera -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCloudera">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCloudlet -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCloudlet">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHardware_Platform"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer_architecture -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer_architecture">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNetwork"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer_cluster -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer_cluster">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTechnology"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTControl_System -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTControl_System">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPurpose-built_Device"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTControl_engineering -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTControl_engineering">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNetwork"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCryptographic_system -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCryptographic_system">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAlgorithm"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_Mining -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_Mining">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAlgorithm"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_analysis -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_analysis">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTechnology"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_center -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_center">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_processing -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_processing">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_transmission -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_transmission">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNetwork"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDeep_learning -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDeep_learning">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTechnology"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDevice -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDevice">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIIoTLayers"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDigital -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDigital">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDevice"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDigital_twin -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDigital_twin">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWeb_Technology"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDistributed_operating_system -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDistributed_operating_system">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDistributed_processing -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDistributed_processing">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData_capability"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDistributed_storage -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDistributed_storage">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData_capability"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDistributed_system -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDistributed_system">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDjango -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDjango">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWeb_Technology"/>
        <owl:disjointWith rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNode"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDrone -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDrone">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPurpose-built_Device"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTE-health -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTE-health">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEddystone -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEddystone">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_application -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_application">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_security -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_security">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_technology"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_technology -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_technology">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTechnology"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_tool -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_tool">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTElectrical_Grids -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTElectrical_Grids">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPurpose-built_Device"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEthics -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEthics">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCapabilities"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFactory_Equipment -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFactory_Equipment">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPurpose-built_Device"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFactory_Floor -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFactory_Floor">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPurpose-built_Device"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFlow -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFlow">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_Photon"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGas_Meter -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGas_Meter">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPurpose-built_Device"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGateway -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGateway">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDevice"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGrid -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGrid">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHAT -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHAT">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">modules that connect processing boards to computers and other objects</rdfs:comment>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHBase -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHBase">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHTTP -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHTTP">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHardware_Platform -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHardware_Platform">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDigital"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHome_automation -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHome_automation">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHortonworks -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHortonworks">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHub -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHub">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTControl_engineering"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTICS -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTICS">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIIoTLayers -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIIoTLayers"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIP -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIP">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIaaS -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIaaS">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCloud_service"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTControl_System"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial_oven -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial_oven">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustry -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustry">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTInternet_standard -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTInternet_standard">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLogic"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIoT_data_processing -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIoT_data_processing">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTJSON_Web_Token -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTJSON_Web_Token">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTInternet_standard"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTJava -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTJava">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProgramming_Language"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTKafka -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTKafka">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDistributed_system"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Kafka, a distributed log messaging system</rdfs:comment>
        <rdfs:label rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Kafka</rdfs:label>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLoRa -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLoRa">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLoRaWAN -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLoRaWAN">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLoRaWan -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLoRaWan">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLoWPAN -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLoWPAN">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLogic -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLogic">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDigital"/>
        <owl:disjointWith rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMQTT -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMQTT">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMQTT_streams -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMQTT_streams">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMachine_Learning -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMachine_Learning">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAlgorithm"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMachine_learning -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMachine_learning">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMahout -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMahout">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMachine_Learning"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTManagement -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTManagement">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCapabilities"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMapR -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMapR">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMedical_devices -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMedical_devices">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMesos -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMesos">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDistributed_operating_system"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicrocontroller -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicrocontroller">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHardware_Platform"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicropayments -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicropayments">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIoT_data_processing"/>
        <owl:disjointWith rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_contracts"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicroprocessor -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicroprocessor">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHardware_Platform"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicroprocessor_Platform -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicroprocessor_Platform">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGateway"/>
        <owl:disjointWith rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_phone"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMllib -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMllib">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMachine_Learning"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMobile_applications -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMobile_applications">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNFC_tag -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNFC_tag">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNetwork -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNetwork">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIIoTLayers"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNetwork_card -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNetwork_card">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer_architecture"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNeural_Network -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNeural_Network">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAlgorithm"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNoSQL_Data -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNoSQL_Data">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNode -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNode">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWeb_Technology"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOSI_stack -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOSI_stack">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOil_Pipeline_Control -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOil_Pipeline_Control">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPurpose-built_Device"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOptical_tag -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOptical_tag">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPAN -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPAN">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPLC -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPLC">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHardware_Platform"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPaaS -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPaaS">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCloud_service"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_Photon -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_Photon">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicrocontroller"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_cloud -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_cloud">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_Photon"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPassive_things -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPassive_things">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPeer-to-peer_system -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPeer-to-peer_system">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPrivacy -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPrivacy">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCapabilities"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProcessing_Board -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProcessing_Board">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProgramming -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProgramming">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProgramming_Language -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProgramming_Language">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLogic"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNetwork"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPurpose-built_Device -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPurpose-built_Device">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDigital"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPython -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPython">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProgramming_Language"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRFID_tag -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRFID_tag">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRTD_sensor -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRTD_sensor">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberry_Pi -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberry_Pi">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicrocontroller"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberyy_Pi -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberyy_Pi">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRuter -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRuter">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTControl_engineering"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSAMPL -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSAMPL">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHardware_Platform"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_capability -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_capability">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_common_protocol -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_common_protocol">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_demand -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_demand">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_problem -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_problem">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_solution -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_solution">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_systems -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_systems">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_today_protocol -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_today_protocol">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSOA -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSOA">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSaaS -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSaaS">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCloud_service"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSatellite -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSatellite">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHardware_Platform"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSecurity -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSecurity">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCapabilities"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDevice"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTShield -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTShield">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">modules that connect processing boards to computers and other objects</rdfs:comment>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDigital"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_cities -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_cities">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_contracts -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_contracts">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIoT_data_processing"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_phone -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_phone">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGateway"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSpark -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSpark">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMachine_Learning"/>
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIIoTLayers"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSwitch -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSwitch">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer_architecture"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTCP -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTCP">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTechnology -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTechnology">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTransducer -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTransducer">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTUDP -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTUDP">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWPAN -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWPAN">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWatson_IoT -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWatson_IoT">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWeb_Technology -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWeb_Technology">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLogic"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWeb_socket -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWeb_socket">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWireless_sensor_network -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWireless_sensor_network">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTXML -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTXML">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTInternet_standard"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTXMPP -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTXMPP">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProtocol"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTYARN -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTYARN">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDistributed_operating_system"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTclimate_control_system -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTclimate_control_system">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThome_health-monitoring_system -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThome_health-monitoring_system">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTiBeacon -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTiBeacon">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Firmware -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Firmware">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAlgorithm"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Subscriber -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Subscriber">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Webhook -->

    <owl:Class rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Webhook">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHTTP"/>
    </owl:Class>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Individuals
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAccess_control -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAccess_control">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApache_Hadoop -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApache_Hadoop">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
        <p:IIoTisToolFor rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLarge_data_stream"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApache_IoT_edge -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApache_IoT_edge">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAuthentication -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAuthentication">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAutonomous_vehicle -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAutonomous_vehicle">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_application"/>
        <p:IIoThasTechnology rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicro_data_center"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAvoid_synchronization -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAvoid_synchronization">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_common_protocol"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAzure_IoT_edge -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAzure_IoT_edge">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBACnet -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBACnet">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_common_protocol"/>
        <p:IIoTLack_security_measure rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTThreats_at_critical_infrastructure"/>
        <p:IIoTProtocols_were_layered rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEthernet"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain-based_edge_level -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain-based_edge_level">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_algorithm -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_algorithm">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain"/>
        <p:IIoThasProblem rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEnergy_managed"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCNTK -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCNTK"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCentralized_service -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCentralized_service"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCloud_gaming -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCloud_gaming">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_application"/>
        <p:IIoThasTechnology rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicro_data_center"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCluster1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCluster1">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer_cluster"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCluster2 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCluster2">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer_cluster"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputational_cost -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputational_cost">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_security"/>
        <p:IIoTbest_Practices rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_grid"/>
        <p:IIoThas_SecuritySolution rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCorrect_Edge_implementation"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCorrect_Edge_implementation -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCorrect_Edge_implementation">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDC1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDC1">
        <p:IIoThasService rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCentralized_service"/>
        <p:IIoTuseAlgorithm rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPaxos"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDC2 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDC2">
        <p:IIoThasService rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAvoid_synchronization"/>
        <p:IIoTuseAlgorithm rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTZookeeper"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDC3 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDC3">
        <p:IIoThasService rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAvoid_synchronization"/>
        <p:IIoTuseAlgorithm rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPaxos"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDC4 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDC4">
        <p:IIoTuseAlgorithm rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPaxos"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_protection -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_protection">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_security_risk -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_security_risk">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_problem"/>
        <p:IIoTcountermeasure rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEnd-to-end_encryption"/>
        <p:IIoTcountermeasure rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTStrong_authentication"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_stream_continue -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_stream_continue">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain"/>
        <p:IIoThasProblem rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTThroughput_limited"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDeep_learning_algorithm -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDeep_learning_algorithm">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDeep_learning"/>
        <p:IIoThasTool rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCNTK"/>
        <p:IIoThasTool rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMXnet"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDisconnect_timeout -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDisconnect_timeout"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDisconnected -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDisconnected"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDistributed_capability -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDistributed_capability">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData_capability"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDoS_attack -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDoS_attack">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_problem"/>
        <p:IIoTcountermeasure rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFirewalls_with_DoS_detection"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEncrypt_messages -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEncrypt_messages">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_security"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEnd-to-end_encryption -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEnd-to-end_encryption">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_solution"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEnergy_managed -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEnergy_managed">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_problem"/>
        <p:IIoThasSolution rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTImprove_central_algorithm"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEthernet -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEthernet">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_today_protocol"/>
        <p:IIoTSupport_communication rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLong-distance_communication"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFireFly -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFireFly">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWireless_sensor_network"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFirewalls_with_DoS_detection -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFirewalls_with_DoS_detection">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_solution"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGroup_services -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGroup_services"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHadoop -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHadoop">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTool"/>
        <p:IIoTisUsedBy rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCluster1"/>
        <p:IIoTisUsedBy rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCluster2"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHigh -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHigh"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIIOT_dual_band_network -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIIOT_dual_band_network">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_technology"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIllegal_transaction -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIllegal_transaction">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_problem"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTImprove_central_algorithm -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTImprove_central_algorithm">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTImproving_data_privacy -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTImproving_data_privacy">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIncreased_storage -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIncreased_storage">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_problem"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIntegrity_assurance -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIntegrity_assurance">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIoT_Connectivity -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIoT_Connectivity">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_problem"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIoT_Privacy -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIoT_Privacy">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_problem"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLarge_data_stream -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLarge_data_stream">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData"/>
        <p:IIoTisProcessed rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDistributed_capability"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLong-distance_communication -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLong-distance_communication">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_capability"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLow -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLow"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMXnet -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMXnet"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMaintain_configuration -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMaintain_configuration"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMapReduce -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMapReduce">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProgramming"/>
        <p:IIoTisApplied rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCluster1"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMemory_size -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMemory_size">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_security"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicro_data_center -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMicro_data_center">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_technology"/>
        <p:IIoThasTool rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAzure_IoT_edge"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTModbus -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTModbus">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_common_protocol"/>
        <p:IIoTLack_security_measure rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTThreats_at_critical_infrastructure"/>
        <p:IIoTProtocols_were_layered rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#TCP/IP"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOPC_servers -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOPC_servers">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_technology"/>
        <p:IIoThasTool rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApache_IoT_edge"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOven1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOven1">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial_oven"/>
        <IIoT:hasTemperatureRange rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">508</IIoT:hasTemperatureRange>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOven2 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOven2">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial_oven"/>
        <IIoT:hasTemperatureRange rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">502</IIoT:hasTemperatureRange>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPassword_mobile_node -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPassword_mobile_node"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPaxos -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPaxos">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_center"/>
        <p:IIoTisApplied rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDC1"/>
        <p:IIoTisApplied rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDC3"/>
        <p:IIoTisApplied rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDC4"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPhoton1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPhoton1">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_Photon"/>
        <p:IIoTwire rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Connection1"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPhoton2 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPhoton2">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_Photon"/>
        <p:IIoTwire rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Connection2"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPredictive_maintenance -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPredictive_maintenance">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_application"/>
        <p:IIoThasTechnology rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOPC_servers"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberyy_Pi_3 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberyy_Pi_3">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberyy_Pi"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberyy_Pi_4B -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberyy_Pi_4B">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberyy_Pi"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTReducing_latency_in_sending_data -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTReducing_latency_in_sending_data">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRemote_management -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRemote_management">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_demand"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRemote_monitoring -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRemote_monitoring">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_demand"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_application -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_application">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA"/>
        <p:IIoTthreats_to_data_security rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_security_risk"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_system -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_system">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSecure_key_management -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSecure_key_management">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSecurity_problem -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSecurity_problem">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_security"/>
        <p:IIoThasSolution rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAccess_control"/>
        <p:IIoThasSolution rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAuthentication"/>
        <p:IIoThasSolution rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_protection"/>
        <p:IIoThasSolution rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIntegrity_assurance"/>
        <p:IIoThasSolution rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSecure_key_management"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSharing_IoT_data -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSharing_IoT_data">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_problem"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_contracts -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_contracts">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain"/>
        <p:IIoThasSecurity_problem rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSecurity_problem"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_grid -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_grid">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_application"/>
        <p:IIoThasTechnology rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOPC_servers"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_home -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_home">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_application"/>
        <p:IIoThasTechnology rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOPC_servers"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTStrong_authentication -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTStrong_authentication">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_solution"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTStrong_password -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTStrong_password">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_security"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSynchronization_in_throughput -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSynchronization_in_throughput">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_solution"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTensor_Flow -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTensor_Flow">
        <p:IIoTisToolFor rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDeep_learning_algorithm"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTheano -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTheano">
        <p:IIoTisToolFor rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDeep_learning_algorithm"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTThreats_at_critical_infrastructure -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTThreats_at_critical_infrastructure">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_problem"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTThroughput_limited -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTThroughput_limited">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBlockchain_problem"/>
        <p:IIoThasSolution rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSynchronization_in_throughput"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTransmission_speed -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTransmission_speed">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_security"/>
        <p:IIoTbest_Practices rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_home"/>
        <p:IIoThas_SecuritySolution rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTReducing_latency_in_sending_data"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTwo-factor_authentication -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTwo-factor_authentication">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_security"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTValue_sent -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTValue_sent">
        <rdf:type>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTValue_sent"/>
                <owl:someValuesFrom>
                    <rdfs:Datatype>
                        <owl:onDatatype rdf:resource="http://www.w3.org/2001/XMLSchema#integer"/>
                        <owl:withRestrictions rdf:parseType="Collection">
                            <rdf:Description>
                                <xsd:minInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">0</xsd:minInclusive>
                            </rdf:Description>
                            <rdf:Description>
                                <xsd:maxInclusive rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">1</xsd:maxInclusive>
                            </rdf:Description>
                        </owl:withRestrictions>
                    </rdfs:Datatype>
                </owl:someValuesFrom>
            </owl:Restriction>
        </rdf:type>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTZookeeper -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTZookeeper">
        <p:IIoThasService rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMaintain_configuration"/>
        <p:IIoTisApplied rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDC2"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Cloud_Photon1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Cloud_Photon1">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_cloud"/>
        <IIoT:request rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Thingspeak1"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Cloud_Photon2 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Cloud_Photon2">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_cloud"/>
        <IIoT:request rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Thingspeak2"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Connection1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Connection1">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFlow"/>
        <IIoT:read rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Particle_publish1"/>
        <IIoT:hasValueConnection rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">1</IIoT:hasValueConnection>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Connection2 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Connection2">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFlow"/>
        <IIoT:read rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Particle_publish2"/>
        <IIoT:hasValueConnection rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">0</IIoT:hasValueConnection>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Oven3 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Oven3">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial_oven"/>
        <IIoT:hasTemperatureRange rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">501</IIoT:hasTemperatureRange>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Oven4 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Oven4">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial_oven"/>
        <IIoT:hasTemperatureRange rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">506</IIoT:hasTemperatureRange>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Oven5 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Oven5">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustrial_oven"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Particle_publish1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Particle_publish1">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Firmware"/>
        <IIoT:send rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Cloud_Photon1"/>
        <IIoT:hasTimeLimit rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">30</IIoT:hasTimeLimit>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Particle_publish2 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Particle_publish2">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Firmware"/>
        <IIoT:send rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Cloud_Photon2"/>
        <IIoT:hasTimeLimit rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">25</IIoT:hasTimeLimit>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Program -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Program">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Firmware"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#RTD3 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#RTD3">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRTD_sensor"/>
        <IIoT:heat rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Oven3"/>
        <IIoT:hasAccuracy rdf:datatype="http://www.w3.org/2001/XMLSchema#decimal">0.6</IIoT:hasAccuracy>
        <IIoT:provideHeat rdf:datatype="http://www.w3.org/2001/XMLSchema#double">510.0</IIoT:provideHeat>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#RTD4 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#RTD4">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRTD_sensor"/>
        <IIoT:heat rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Oven4"/>
        <IIoT:hasAccuracy rdf:datatype="http://www.w3.org/2001/XMLSchema#decimal">0.8</IIoT:hasAccuracy>
        <IIoT:provideHeat rdf:datatype="http://www.w3.org/2001/XMLSchema#double">520.0</IIoT:provideHeat>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#RTD5 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#RTD5">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRTD_sensor"/>
        <IIoT:heat rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Oven5"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#RTDsensor1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#RTDsensor1">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRTD_sensor"/>
        <IIoT:heat rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOven1"/>
        <IIoT:hasAccuracy rdf:datatype="http://www.w3.org/2001/XMLSchema#decimal">0.5</IIoT:hasAccuracy>
        <IIoT:provideHeat rdf:datatype="http://www.w3.org/2001/XMLSchema#double">480.0</IIoT:provideHeat>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#RTDsensor2 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#RTDsensor2">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRTD_sensor"/>
        <IIoT:heat rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOven2"/>
        <IIoT:hasAccuracy rdf:datatype="http://www.w3.org/2001/XMLSchema#decimal">0.3</IIoT:hasAccuracy>
        <IIoT:provideHeat rdf:datatype="http://www.w3.org/2001/XMLSchema#double">500.0</IIoT:provideHeat>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Request1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Request1"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Request2 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Request2"/>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Thingspeak1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Thingspeak1">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Subscriber"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Thingspeak2 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Thingspeak2">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#Subscriber"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#5G_Pervasive_Edge_Computing -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#5G_Pervasive_Edge_Computing">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEdge_application"/>
        <p:IIoThasTechnology rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIIOT_dual_band_network"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#TCP/IP -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#TCP/IP">
        <rdf:type rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSCADA_today_protocol"/>
        <p:IIoTSupport_communication rdf:resource="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLong-distance_communication"/>
    </owl:NamedIndividual>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // General axioms
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAgriculture"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData_app"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTE-health"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIndustry"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMachine_learning"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSOA"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_cities"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWeb_socket"/>
        </owl:members>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAlgorithm"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTProgramming_Language"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWeb_Technology"/>
        </owl:members>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTAnalytics"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_Mining"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMachine_Learning"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNeural_Network"/>
        </owl:members>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTApplication"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTCapabilities"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDevice"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNetwork"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSupport"/>
        </owl:members>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTArduino"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTParticle_Photon"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRaspberry_Pi"/>
        </owl:members>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBLE"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHTTP"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTIP"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLoWPAN"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMQTT"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTNFC_tag"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOptical_tag"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPAN"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTRFID_tag"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSAMPL"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTTCP"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTUDP"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWPAN"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTXMPP"/>
        </owl:members>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTBigData_app"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMachine_learning"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSOA"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTWeb_socket"/>
        </owl:members>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTC"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTJava"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPython"/>
        </owl:members>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTComputer_architecture"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTControl_engineering"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTData_transmission"/>
        </owl:members>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTControl_System"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTElectrical_Grids"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFactory_Equipment"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTFactory_Floor"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGas_Meter"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTOil_Pipeline_Control"/>
        </owl:members>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTDigital"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTGateway"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSensor_Actuator"/>
        </owl:members>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTEddystone"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHome_automation"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMedical_devices"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMobile_applications"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTclimate_control_system"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoThome_health-monitoring_system"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTiBeacon"/>
        </owl:members>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTHardware_Platform"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTLogic"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTPurpose-built_Device"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSmart_Product"/>
        </owl:members>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMahout"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTMllib"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoTSpark"/>
        </owl:members>
    </rdf:Description>
    

  </rdf:RDF>

<!-- Generated by the OWL API (version 4.5.9.2019-02-01T07:24:44Z) https://github.com/owlcs/owlapi -->
