Zen Cart Editable Invoices & Packing Slips Module v 1.0.0
Version Release Date: 4/8/2015
Publisher: PRO-Webs, Inc
Released for Zen Cart v 1.3.x & 1.5.X

This installation is considered a intermediate level Zen Cart module installation.

This Zen Cart module will add an editable region to admin invoices & packing slips.
The editable regions are accessible via Tools >> Define Pages Editor in your Zen
Cart admin.

This installation contains only Zen Cart 1.5.4 files and you will need to carefully 
the commented changes for other versions.


INSTALLATION INSTRUCTIONS
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

1. FIRST MAKE A FULL BACKUP OF YOUR WEBSITE'S FILES AND DATABASE!

2. Upload/merge the files in the catalog directory with your own
   Zen Cart files.
   
3. In your Zen Cart admin under Tools >> Define Pages Editor define 
   the text you wish to appear on each. (SEE TIPS BELOW)
      

INFORMATION
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Core file Edits: admin/packingslip.php & admin/invoice.php
Database Changes: None


UNINSTALL
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Simply remove the package files & edits for a full uninstall.


SUPPORT
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Please seek support here https://pro-webs-support.com/


VERSION HISTORY
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Original Release PRO-Webs.net 04/08/2015

Cool Tips
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
We wrote this for a customer who wanted to include specifically their returns
information as well as the return address on packing slips to make returns
easier for their customers. You can easily use a RMA number in the address which
includes the order number for easy identification when returns are received like 
below.

<h3>Please ship your return to</h3>
<p>Your Company Name<br />
RMA#<?php echo $oID; ?><br />
Street Address<br />
City, State 00000</p>