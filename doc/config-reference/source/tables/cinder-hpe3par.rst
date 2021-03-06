..
    Warning: Do not edit this file. It is automatically generated from the
    software project's code and your changes will be overwritten.

    The tool to generate this file lives in openstack-doc-tools repository.

    Please make any changes needed in the code, then run the
    autogenerate-config-doc tool from the openstack-doc-tools repository, or
    ask for help on the documentation mailing list, IRC channel or meeting.

.. _cinder-hpe3par:

.. list-table:: Description of HPE 3PAR Fibre Channel and iSCSI drivers configuration options
   :header-rows: 1
   :class: config-ref-table

   * - Configuration option = Default value
     - Description
   * - **[DEFAULT]**
     -
   * - ``hpe3par_api_url`` =
     - (String) 3PAR WSAPI Server Url like https://<3par ip>:8080/api/v1
   * - ``hpe3par_cpg`` = ``OpenStack``
     - (List) List of the CPG(s) to use for volume creation
   * - ``hpe3par_cpg_snap`` =
     - (String) The CPG to use for Snapshots for volumes. If empty the userCPG will be used.
   * - ``hpe3par_debug`` = ``False``
     - (Boolean) Enable HTTP debugging to 3PAR
   * - ``hpe3par_iscsi_chap_enabled`` = ``False``
     - (Boolean) Enable CHAP authentication for iSCSI connections.
   * - ``hpe3par_iscsi_ips`` =
     - (List) List of target iSCSI addresses to use.
   * - ``hpe3par_password`` =
     - (String) 3PAR password for the user specified in hpe3par_username
   * - ``hpe3par_snapshot_expiration`` =
     - (String) The time in hours when a snapshot expires and is deleted. This must be larger than expiration
   * - ``hpe3par_snapshot_retention`` =
     - (String) The time in hours to retain a snapshot. You can't delete it before this expires.
   * - ``hpe3par_username`` =
     - (String) 3PAR username with the 'edit' role
