# geniki-taxydromiki-tracking

A "geniki taxydromiki" parcel tracking solution that can be integrated with [ntfy](http://ntfy.sh) or run standalone.

### Usage
- **_No ntfy integration:_**
  - Widnows:
    ```
    python geniki_taxydromiki.py <tracking-number>
    ```
  - Linux:
    ```
    python3 geniki_taxydromiki.py <tracking-number>
    ```
- **_With ntfy integration:_**
  - Widnows:
    ```
    python geniki_taxydromiki.py <ntfy-server> <ntfy-topic> <tracking-number>
    ```
  - Linux:
    ```
    python3 geniki_taxydromiki.py <ntfy-server> <ntfy-topic> <tracking-number>
    ```
