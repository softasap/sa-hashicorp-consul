sa-hashicorp-consul
===================

[![Build Status](https://travis-ci.org/softasap/sa-hashicorp-consul.svg?branch=master)](https://travis-ci.org/softasap/sa-hashicorp-consul)


Example of usage (all parameters are optional)

Simple

  roles:
    - {
        role: "sa-hashicorp-consul"
      }


Advanced:


  roles:
    - {
        role: "sa-hashicorp-consul",
        consul_version: 0.6.15,
        consul_platform: linux,
        consul_path: /usr/local/bin
      }



