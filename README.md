# BMW Gehänge Halteöse Reverse Engineering Documentation
## Project Code: HK37F

### Executive Summary
This document provides comprehensive reverse engineering analysis of the BMW Gehänge Halteöse component. Compatibility matrices across BMW and Mini Group platforms are included to address a critical design flaw.

The original OEM appears to have inadequately addressed material selection, as approximately every fourth car experiences failure at this attachment point within the parcel shelf clip assembly. The OEM specification utilizes ABS plastic, which has proven insufficient for the mechanical loads encountered.
 
### Solution

<div style="display: flex; gap: 10px;">
<img src="https://0x0.st/KoUR.jpeg" alt="Solution Image 1" width="15%">
<img src="https://0x0.st/KoU7.jpeg" alt="Solution Image 2" width="15%">
</div>

.STL can be used commercially and is for sale [here](https://www.printables.com/model/1311738-kommerzielle-lizenz-bmwmini-1-series-f20-x1-mini-c)

### Compatibility Matrix
see PDF [Kompatibilitätsliste](./HK37F-Kompatibilitätsliste.pdf)

### Help with updating the list 

If you know of any additional vehicles (especially vehicles by the Mini Group) also using the same parcel shelf attachment system, feel free to append them to the compatibility list.

Finally compile the quarkdown document into a PDF with this:

```bash
./quarkdown HK37F-Kompatibilitätsliste.qmd --pdf
