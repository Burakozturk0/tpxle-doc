``` js

{
  "deviceEUI" : "20635f028100003e",
  "time" : "2022-09-02T07:42:56.273Z",
  "customerId" : "100009247",
  "modelCfg" : "1:TPX_ba3df8fb-bc93-45ee-aa0d-b2f873b9bbc6",
  "dxProfileId" : "community-api",
  "coordinates" : [ 103.92496472, 1.31509533, 0.0 ],
  "age" : 0,
  "validityState" : "NEW",
  "horizontalAccuracy" : 30,
  "incomingSubscriberId" : "100009247",
  "processedFeed" : {
    "SF" : 10,
    "deviceProfileId" : "ABEEWAY/MICRO",
    "payloadEncoded" : "0a503295a008",
    "sequenceNumber" : 18504,
    "receptionTime" : "2022-09-02T07:42:56.273Z",
    "dynamicMotionState" : "STATIC",
    "temperatureMeasure" : 31.37647,
    "processedPacket" : {
      "SNR" : 8.5,
      "RSSI" : -72.0,
      "baseStationId" : "100008CE",
      "antennaCoordinates" : [ 103.924858, 1.314996 ]
    },
    "port" : 18
  },
  "resolvedTracker" : {
    "firmwareVersion" : "2.3.1",
    "bleFirmwareVersion" : "3.3.3",
    "messageType" : "EVENT",
    "shutdownCause" : "UNKNOWN",
    "trackingMode" : "PERMANENT_TRACKING",
    "gpsScanMode" : "UNKNOWN",
    "sensorMode" : "UNKNOWN",
    "periodicPositionInterval" : 3600,
    "batteryLevel" : 50,
    "batteryStatus" : "OPERATING",
    "sosFlag" : true,
    "activityCount" : -1,
    "trackingUlPeriod" : 30,
    "loralivePeriod" : 600,
    "energyStatusPeriod" : 0,
    "geolocSensorProfile" : "WIFI_ONLY",
    "oneshotGeolocMethod" : "GPS",
    "extAntennaProfile" : "UNKNOWN",
    "motionStartEndNbTx" : -1,
    "gpsTimeout" : -1,
    "xgpsTimeout" : -1,
    "gpsEHPE" : 20,
    "gpsConvergence" : 30,
    "transmitStrat" : "CUSTOM_STRATEGY",
    "bleBeaconCount" : -1,
    "bleBeaconTimeout" : -1,
    "gpsStandbyTimeout" : -1,
    "confirmedUlBitmap" : 0,
    "confirmedUlRetry" : 3,
    "motionSensitivity" : -1,
    "shockDetection" : -1,
    "periodicActivityPeriod" : -1,
    "motionDuration" : -1,
    "bleRssiFilter" : -1,
    "temperatureHigh" : -1.0,
    "temperatureLow" : -1.0,
    "temperatureAction" : "UNKNOWN",
    "bleBond" : "UNKNOWN",
    "transmitStratCustom" : {
      "ADREnabled" : false,
      "transmissionType" : "SINGLE",
      "firstTransmissionDatarateDistribution" : "RANDOM",
      "secondTransmissionDatarateDistribution" : "RANDOM",
      "firstTransmissionDatarate" : {
        "dr0" : false,
        "dr1" : false,
        "dr2" : true,
        "dr3" : false,
        "dr4" : false,
        "dr5" : false,
        "dr6" : false,
        "dr7" : false
      },
      "secondTransmissionDatarate" : {
        "dr0" : false,
        "dr1" : false,
        "dr2" : false,
        "dr3" : false,
        "dr4" : false,
        "dr5" : false,
        "dr6" : false,
        "dr7" : false
      }
    },
    "batteryCapacity" : -1,
    "reedSwitchConfiguration" : "UNKNOWN",
    "collectionScanType" : "UNKNOWN",
    "collectionBLEFilterType" : "UNKNOWN",
    "collectionBLEFilterMain1" : -1,
    "collectionBLEFilterMain2" : -1,
    "collectionBLEFilterSecValue" : -1,
    "collectionBLEFilterSecMask" : -1,
    "collectionNbEntry" : -1,
    "networkTimeoutCheck" : -1,
    "networkTimeoutReset" : -1
  },
  "uplinkPayload" : {
    "messageType" : "EVENT",
    "trackingMode" : "PERMANENT_TRACKING",
    "batteryLevel" : 50,
    "batteryStatus" : "OPERATING",
    "ackToken" : 10,
    "periodicPosition" : false,
    "temperatureMeasure" : 31.4,
    "sosFlag" : 1,
    "appState" : 0,
    "dynamicMotionState" : "STATIC",
    "onDemand" : false,
    "payload" : "0a503295a008",
    "deviceConfiguration" : {
      "mode" : "PERMANENT_TRACKING"
    },
    "eventType" : "SOS_MODE_END"
  },
  "resolvedTrackerParameters" : {
    "mode" : "PERMANENT_TRACKING",
    "firmwareVersion" : "2.3.1",
    "bleFirmwareVersion" : "3.3.3",
    "trackingUlPeriod" : 30,
    "geolocSensorProfile" : "WIFI_ONLY",
    "oneshotGeolocMethod" : "GPS",
    "gpsEhpe" : 20,
    "gpsConvergence" : 30,
    "transmitStrat" : "CUSTOM_STRATEGY",
    "loralivePeriod" : 600,
    "energyStatusPeriod" : 0,
    "periodicPositionInterval" : 3600,
    "transmitStratCustom" : {
      "adrEnabled" : 0,
      "transmissionType" : "SINGLE",
      "firstTransmissionDatarateDistribution" : "RANDOM",
      "secondTransmissionDatarateDistribution" : "RANDOM",
      "firstTransmissionDatarate" : {
        "dr0" : 0,
        "dr1" : 0,
        "dr2" : 1,
        "dr3" : 0,
        "dr4" : 0,
        "dr5" : 0,
        "dr6" : 0,
        "dr7" : 0
      },
      "secondTransmissionDatarate" : {
        "dr0" : 0,
        "dr1" : 0,
        "dr2" : 0,
        "dr3" : 0,
        "dr4" : 0,
        "dr5" : 0,
        "dr6" : 0,
        "dr7" : 0
      }
    },
    "defaultProfile" : "UNKNOWN",
    "dynamicProfile" : "Unknown",
    "unknown" : 0,
    "periodicPositionPeriod" : 3600,
    "confirmedUplink" : {
      "framePending" : false,
      "position" : false,
      "energyStatus" : false,
      "healthStatus" : false,
      "heartbeat" : false,
      "activityStatus" : false,
      "configuration" : false,
      "shockDetection" : false,
      "shutdown" : false,
      "event" : false,
      "scanCollection" : false,
      "extendedPosition" : false,
      "debug" : false,
      "confirmedUlBitmap" : 0,
      "confirmedUlRetry" : 3
    },
    "confirmedUlBitmap" : 0,
    "confirmedUlRetry" : 3
  },
  "messageSource" : "LORA",
  "downlinkUrl" : "https://community.thingpark.io/iot-flow/downlinkMessages/6f7b1b1a-5887-447d-a734-014a4e6926a9"
}
``` 