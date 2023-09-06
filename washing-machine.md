# Washing machine state

## START
topic:v1cdti/app/get/6310301034/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Status",
    "value"     :   "Start"
}

## READY
topic:v1cdti/app/get/6310301034/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Status",
    "value"     :   "READY"
}

## FILLWATER
topic:v1cdti/app/get/6310301034/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Status",
    "value"     :   "Fillwater_ON"
}

## HEATWATER
topic:v1cdti/app/get/631030134/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Status",
    "value"     :   "Heatwater_ON"
}

## WASH
topic:v1cdti/app/get/6310301034/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Status",
    "value"     :   "Wash_ON"
}

## RINSE
topic:v1cdti/app/get/6310301034/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Status",
    "value"     :   "Rinse_ON"
}

## SPIN
topic:v1cdti/app/get/6310301034/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Status",
    "value"     :   "Spin_ON"
}

# Operation state

## DOORCLOSE
topic:v1cdti/app/get/6310301034/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "OP_status_Doorclose",
    "value"     :   "Doorclose_ON"
}

## WATERFULLLEVEL
topic:v1cdti/app/get/6310301034/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "OP_status_waterfulllevel",
    "value"     :   "waterfulllevel"
}

## TEMPERATUREREACHED
topic:v1cdti/app/get/6310301034/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "OP_Status_Temperaturereached",
    "value"     :   "Temperaturereached"
}


# FAULT state
topic:v1cdti/app/get/6310301034/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Fault_Status_Timeout",
    "value"     :   "Fault"
}


## TIMEOUT
topic:v1cdti/app/get/6310301034/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Fault_Status_Timeout",
    "value"     :   "Timeout"
}

## OUTOFBALANCE
topic:v1cdti/app/get/6310301034/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Fault_Status_Outofbalance",
    "value"     :   "Outofbalance"
}

## MOTORFAILURE
topic:v1cdti/app/get/6310301034/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Fault_Status_Motorfailure",
    "value"     :   "Motorfailure"
}

## FAULTCLEARED
topic:v1cdti/app/get/6310301034/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301034",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Fault_Status_Faultcleared",
    "value"     :   "Ready"
}