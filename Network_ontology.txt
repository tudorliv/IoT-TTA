@prefix : 		<http://visualdataweb.org/IIoT/> .
@prefix rdf: 		<http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix rdfs: 		<http://www.w3.org/2000/01/rdf-schema#> .
@prefix owl: 		<http://www.w3.org/2002/07/owl#> .
@prefix xsd: 		<http://www.w3.org/2001/XMLSchema#> .
@prefix dc: 		<http://purl.org/dc/elements/1.1/> .
@prefix xml: 		<http://www.w3.org/XML/1998/namespace> .
@prefix wot: 		<http://xmlns.com/wot/0.1/> .
@prefix vs: 		<http://www.w3.org/2003/06/sw-vocab-status/ns#> .
@prefix foaf: 		<http://xmlns.com/foaf/0.1/> .
@prefix : 		<http://www.semanticweb.org/IoT-WG/ontologies/2022/3/IIoT#> .
@base 			<http://visualdataweb.org/IIoT/> .

<http://visualdataweb.org/IIoT/> rdf:type owl:Ontology ;
                                 dc:title "IoT-Network"@en; 
                                 dc:description "Network ontology description"@en; 
                                 owl:versionInfo "1.2"@en. 

:data transfer rdf:type owl:ObjectProperty ;
               rdfs:label "data transfer"@en; 
               rdfs:domain :MQTT;
               rdfs:range :Device . 
:isIdentified rdf:type owl:ObjectProperty ;
              rdfs:label "isIdentified"@en; 
              rdfs:domain :Passive things;
              rdfs:range http://visualdataweb.org/IIoT/NFC/RFID/optical tag . 
:isUsedIn rdf:type owl:ObjectProperty ;
          rdfs:label "isUsedIn"@en; 
          rdfs:domain :MQTT;
          rdfs:range :Smart product . 
:undefined rdf:type owl:ObjectProperty ;
           rdfs:label "isUsedIn"@en; 
           rdfs:domain :MQTT;
           rdfs:range :Hardware platform . 
:sIdentified rdf:type owl:ObjectProperty ;
             rdfs:label "isIdentified"@en; 
             rdfs:domain :Passive things;
             rdfs:range :BLE beacons . 
:authentication rdf:type owl:ObjectProperty ;
                rdfs:label "authentication"@en; 
                rdfs:domain :MQTT;
                rdfs:range :asymmetric public keys . 
:authentication2 rdf:type owl:ObjectProperty ;
                 rdfs:label "authentication"@en; 
                 rdfs:domain :MQTT;
                 rdfs:range :JSON Web token . 

<http://visualdataweb.org/newOntology/Network> rdf:type owl:Class; 
                                               rdfs:label "Network"@en . 
<http://visualdataweb.org/newOntology/Protocol> rdf:type owl:Class; 
                                                rdfs:subClassOf <http://visualdataweb.org/newOntology/Network> ;
                                                rdfs:label "Protocol"@en . 
http://visualdataweb.org/newOntology/Computer architecture rdf:type owl:Class; 
                                                           rdfs:subClassOf <http://visualdataweb.org/newOntology/Network> ;
                                                           rdfs:label "Computer architecture"@en . 
:Control engineering rdf:type owl:Class; 
                     rdfs:subClassOf <http://visualdataweb.org/newOntology/Network> ;
                     rdfs:label "Control engineering"@en . 
:Data transmission rdf:type owl:Class; 
                   rdfs:subClassOf <http://visualdataweb.org/newOntology/Network> ;
                   owl:disjointWith :Control engineering ;
                   owl:disjointWith http://visualdataweb.org/newOntology/Computer architecture ;
                   rdfs:label "Data transmission"@en . 
:MQTT rdf:type owl:Class; 
      rdfs:subClassOf <http://visualdataweb.org/newOntology/Protocol> ;
      rdfs:label "MQTT"@en . 
:Device rdf:type owl:Class; 
        rdfs:label "Device"@en . 
http://visualdataweb.org/IIoT/NFC/RFID/optical tag rdf:type owl:Class; 
                                                   rdfs:subClassOf <http://visualdataweb.org/newOntology/Protocol> ;
                                                   owl:disjointWith :BLE beacons ;
                                                   rdfs:label "NFC/RFID/optical tag"@en . 
:Passive things rdf:type owl:Class; 
                rdfs:label "Passive things"@en . 
:Smart product rdf:type owl:Class; 
               rdfs:subClassOf :Digital ;
               rdfs:label "Smart product"@en . 
:Hardware platform rdf:type owl:Class; 
                   owl:disjointWith :Smart product ;
                   rdfs:subClassOf :Digital ;
                   rdfs:label "Hardware platform"@en . 
:BLE beacons rdf:type owl:Class; 
             rdfs:subClassOf <http://visualdataweb.org/newOntology/Protocol> ;
             rdfs:label "BLE beacons"@en . 
:asymmetric public keys rdf:type owl:Class; 
                        rdfs:label "asymmetric public keys"@en . 
:JSON Web token rdf:type owl:Class; 
                rdfs:label "JSON Web token"@en . 
:Digital rdf:type owl:Class; 
         rdfs:subClassOf :Device ;
         rdfs:label "Digital"@en . 
