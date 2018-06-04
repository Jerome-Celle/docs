==============================
Configured pick batch programs
==============================

Printing pick batches
=====================
Here is the list of various standard pick batch print out programs:

HFMI23
------
    Allows PNs and labels to be edited when printing and reprinting.

    The PNs are the PNs that are specific to each type of pick:

    - For PCC and RCC picks: **HFMI35**
    - For DPP and DPS picks: **HFMI36**
    - For DRP and DRS: **HFMI37**
    - For MIX picks: **HFMI38**

HFM127
------
  Allows you to specify that PNs and labels can be edited when printing and reprinting.

  The PNs are the standard PNs for all pick types (HFMI38).

HFMI29
------
  Does not allow anything to be edited when printing and allows PNs and labels to be edited when
  reprinting.
  The PNs are the standard PNs for all pick types (HFMI38).

  If, at the work mode/pick type configuration level, the printing mode selected for pick batches is
  "Standard", and the processing chain is not a prepacking chain, HFMI29 is the program used by
  default.

HFMI2B
------
  Allows you to specify that no PNs and labels can be edited when printing and that only PNs can be
  edited when reprinting.

  The PNs are the standard PNs for all pick types (HFMI38).

HFMI2D
------
  Allows you to specify that only PNs can be edited when printing and reprinting.
  The PNs are the standard PNs for all pick types (HFMI38).

HFMI2F
------
  Only applies to DPP, DPS and mixed pick batches, in the context of prepacking.
  Allows you to specify that PNs can be edited when printing and reprinting.
  The PNs are the standard prepacking PNs for all pick types (HFMI38).

  Allows carton, pick batch start and pick batch end labels to be printed.
  Reminder: The printed carton label is the one defined in the configuration at work mode/pick type
  level.

  If, at the work mode/pick type configuration level, the printing mode selected for pick batches is
  "Standard", and if the processing chain is not a prepacking chain, HFMI2F is the program used by
  default.

HFMI2M
------
  Only applies to DPP, DPS and mixed pick batches, in the context of prepacking.
  Allows you to specify that neither PNs nor labels can be edited when printing and reprinting
  (preparation calculation).

  Allows labels to be edited (pick batch start, carton, pick batch end) when reprinting.
  This program must be configured for a work mode/pick type when the carton labels are printed when
  the pick batch is handled (work mode/procedure configuration).

  Reminder: The printed carton label is the one defined in the configuration at work mode/pick type
  level.

HFMI2N
------
  Only applies to DPS pick batches, in the context of deconsolidation.
  Allows pick batch labels to be edited (HFMI45) when printing and pick batch labels and PNs to be
  edited when reprinting.

  The PNs are the standard PNs for all pick types.

HFMI2P
------
  If, at the work mode/pick type configuration level, the printing mode selected for pick batches is
  "Standard", then HFMI2F is the program used by default.

  It applies to all pick types and takes into account the configuration linked to the printing of
  customisable PNs on the screen used for defining the work mode/pick type.

  A program configuration allows you to specify when the labels should be printed:

  - on pick run,
  - On request
  - On pick run and on request,

  Not at all

  In the same way, a program configuration allows you to specify whether or the preparation note is
  printed on pick run/on request.