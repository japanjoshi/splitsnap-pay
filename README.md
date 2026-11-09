# SplitSnap pay page

The tap-to-pay page SplitSnap links friends to. Everything a link carries (UPI ID, amount, note) sits after
the `#`, which browsers never send to the server, so this host sees none of it and nothing is stored.

The source lives in the SplitSnap app repo under `paylink/`; this repo only hosts a copy.
