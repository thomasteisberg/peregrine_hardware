# Peregrine Hardware FIles

This repository contains hardware design and fabrication files for the Peregrine UAV-borne radio echo sounder (Part of the ORCA project)

See https://orca.radioglaciology.com/docs/peregrine/ for details

Design files produced by us are available under an [MIT License](LICENSE). For vendor CAD, please check with individual vendors.

## Payload Enclosure

<img src="payload_enclosure/img/payload_enclosure_pi4_onscale.png" width="50%" alt="Photo of an assembled payload enclosure" />

The [payload enclosure](payload_enclosure/README.md) is the box containing the Ettus b205-mini SDR and the Raspberry Pi for the Peregrine UAS.

This assembly normally lives in the nosecone of the Peregrine UAV, as seen in the photo below, however it can be re-purpose in other ways.

<img src="payload_enclosure/img/peregrine_from_front.jpg" alt="Front view of the Peregrine UAS showing the payload enclousure within the nosecone" width="50%" />

## Payload enclosure PCBs

There are two custom PCBs that live inside the payload enclosure. They are:

* [Peregrine Pi Hat](pcbs/pi_hat/README.md)
* [Peregrine Payload Divider](pcbs/payload_divider/README.md)

## Antennas

<img src="antennas/underwing_bowtie_antennas/bowtie_on_scale.jpg" alt="Bowtie antenna on a scale" width="50%" />

* [Peregrine under-wing edge-cut bowtie antennas](antennas/underwing_bowtie_antennas/README.md)