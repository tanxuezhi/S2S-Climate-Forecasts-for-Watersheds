# Download NMME data from IRI in real-time
crontab executes `exec_process_nmme_iri.bash` which calls the scripts below.

### Download nmme for current month (after the 8th)
`dwnld_nmme_fcsts_iri.csh`

### Process and average to HUCs
`process_nmme_fcst_iri.csh`

### Process for shiny app and copies over to web server
`process_nmme_realtime_iri.Rscr`
