# OmniORB - getting started

## 1. Create and activate a CONDA env

    $ conda create -n omni-env -c conda-forge python=3.10 omniorb omniorbpy

    $ conda activate omni-env

## 2. Generate Python Code from IDL

    $ omniidl -bpython Example.idl

## 3. Run the OmniORB Service:

    $ omniNames -start

## 3. Run the Server:

    $ python Server.py

## 4. Run the Client:

    $ python Client.py

## 5. Enter the IOR obtained from the server terminal:

    $ Enter IOR of Greetings object:

    IOR:010000001a00000049444c3a4578616d706c652f4772656574696e67733a312e30000000010000000000000068000000010102000f0000003139322e3136382e33312e3136300000538e00000e000000fe9f4a246500002964000000000000000200000000000000080000000100000000545441010000001c00000001000000010001000100000001000105090101000100000009010100

    Message from server: Hello from OmniORBpy!
