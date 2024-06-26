# Table of contents

* [Introduction to DNSControl](index.md)

## Getting Started

* [Overview](getting-started.md)
* [Examples](examples.md)
* [Migrating zones to DNSControl](migrating.md)
* [TypeScript autocomplete and type checking](typescript.md)

## Language Reference

* [JavaScript DSL](js.md)
* Top Level Functions
  * [D](language-reference/top-level-functions/D.md)
  * [DEFAULTS](language-reference/top-level-functions/DEFAULTS.md)
  * [DOMAIN_ELSEWHERE](language-reference/top-level-functions/DOMAIN_ELSEWHERE.md)
  * [DOMAIN_ELSEWHERE_AUTO](language-reference/top-level-functions/DOMAIN_ELSEWHERE_AUTO.md)
  * [D_EXTEND](language-reference/top-level-functions/D_EXTEND.md)
  * [FETCH](language-reference/top-level-functions/FETCH.md)
  * [IP](language-reference/top-level-functions/IP.md)
  * [NewDnsProvider](language-reference/top-level-functions/NewDnsProvider.md)
  * [NewRegistrar](language-reference/top-level-functions/NewRegistrar.md)
  * [PANIC](language-reference/top-level-functions/PANIC.md)
  * [REV](language-reference/top-level-functions/REV.md)
  * [getConfiguredDomains](language-reference/top-level-functions/getConfiguredDomains.md)
  * [require](language-reference/top-level-functions/require.md)
  * [require_glob](language-reference/top-level-functions/require_glob.md)
* Domain Modifiers
    * [A](language-reference/domain-modifiers/A.md)
    * [AAAA](language-reference/domain-modifiers/AAAA.md)
    * [ALIAS](language-reference/domain-modifiers/ALIAS.md)
    * [AUTODNSSEC_OFF](language-reference/domain-modifiers/AUTODNSSEC_OFF.md)
    * [AUTODNSSEC_ON](language-reference/domain-modifiers/AUTODNSSEC_ON.md)
    * [CAA](language-reference/domain-modifiers/CAA.md)
    * [CAA_BUILDER](language-reference/domain-modifiers/CAA_BUILDER.md)
    * [CNAME](language-reference/domain-modifiers/CNAME.md)
    * [DHCID](language-reference/domain-modifiers/DHCID.md)
    * [DNAME](language-reference/domain-modifiers/DNAME.md)
    * [DISABLE_IGNORE_SAFETY_CHECK](language-reference/domain-modifiers/DISABLE_IGNORE_SAFETY_CHECK.md)
    * [DMARC_BUILDER](language-reference/domain-modifiers/DMARC_BUILDER.md)
    * [DS](language-reference/domain-modifiers/DS.md)
    * [DefaultTTL](language-reference/domain-modifiers/DefaultTTL.md)
    * [DnsProvider](language-reference/domain-modifiers/DnsProvider.md)
    * [FRAME](language-reference/domain-modifiers/FRAME.md)
    * [IGNORE](language-reference/domain-modifiers/IGNORE.md)
    * [IGNORE_NAME](language-reference/domain-modifiers/IGNORE_NAME.md)
    * [IGNORE_TARGET](language-reference/domain-modifiers/IGNORE_TARGET.md)
    * [IMPORT_TRANSFORM](language-reference/domain-modifiers/IMPORT_TRANSFORM.md)
    * [INCLUDE](language-reference/domain-modifiers/INCLUDE.md)
    * [LOC](language-reference/domain-modifiers/LOC.md)
    * [LOC_BUILDER_DD](language-reference/domain-modifiers/LOC_BUILDER_DD.md)
    * [LOC_BUILDER_DMM_STR](language-reference/domain-modifiers/LOC_BUILDER_DMM_STR.md)
    * [LOC_BUILDER_DMS_STR](language-reference/domain-modifiers/LOC_BUILDER_DMS_STR.md)
    * [LOC_BUILDER_STR](language-reference/domain-modifiers/LOC_BUILDER_STR.md)
    * [M365_BUILDER](language-reference/domain-modifiers/M365_BUILDER.md)
    * [MX](language-reference/domain-modifiers/MX.md)
    * [NAMESERVER](language-reference/domain-modifiers/NAMESERVER.md)
    * [NAMESERVER_TTL](language-reference/domain-modifiers/NAMESERVER_TTL.md)
    * [NAPTR](language-reference/domain-modifiers/NAPTR.md)
    * [NO_PURGE](language-reference/domain-modifiers/NO_PURGE.md)
    * [NS](language-reference/domain-modifiers/NS.md)
    * [PTR](language-reference/domain-modifiers/PTR.md)
    * [PURGE](language-reference/domain-modifiers/PURGE.md)
    * [SOA](language-reference/domain-modifiers/SOA.md)
    * [SPF_BUILDER](language-reference/domain-modifiers/SPF_BUILDER.md)
    * [SRV](language-reference/domain-modifiers/SRV.md)
    * [SSHFP](language-reference/domain-modifiers/SSHFP.md)
    * [TLSA](language-reference/domain-modifiers/TLSA.md)
    * [TXT](language-reference/domain-modifiers/TXT.md)
    * [URL](language-reference/domain-modifiers/URL.md)
    * [URL301](language-reference/domain-modifiers/URL301.md)
    * Service Provider specific
        * Akamai Edge Dns
            * [AKAMAICDN](language-reference/domain-modifiers/AKAMAICDN.md)
        * Amazon Route 53
            * [R53_ALIAS](language-reference/domain-modifiers/R53_ALIAS.md)
        * Azure DNS
            * [AZURE_ALIAS](language-reference/domain-modifiers/AZURE_ALIAS.md)
        * Cloudflare DNS
            * [CF_REDIRECT](language-reference/domain-modifiers/CF_REDIRECT.md)
            * [CF_TEMP_REDIRECT](language-reference/domain-modifiers/CF_TEMP_REDIRECT.md)
            * [CF_WORKER_ROUTE](language-reference/domain-modifiers/CF_WORKER_ROUTE.md)
        * ClouDNS
            * [CLOUDNS_WR](language-reference/domain-modifiers/CLOUDNS_WR.md)
        * NS1
            * [NS1_URLFWD](language-reference/domain-modifiers/NS1_URLFWD.md)
* Record Modifiers
    * [TTL](language-reference/record-modifiers/TTL.md)
    * Service Provider specific
        * Amazon Route 53
            * [R53_ZONE](language-reference/record-modifiers/R53_ZONE.md)
            * [R53_EVALUATE_TARGET_HEALTH](language-reference/record-modifiers/R53\_EVALUATE\_TARGET\_HEALTH.md)
* [Why CNAME/MX/NS targets require a "dot"](why-the-dot.md)

## Service Providers

* [Providers](providers.md)
    * [Akamai Edge DNS](providers/akamaiedgedns.md)
    * [Amazon Route 53](providers/route53.md)
    * [AutoDNS](providers/autodns.md)
    * [AXFR+DDNS](providers/axfrddns.md)
    * [Azure DNS](providers/azure_dns.md)
    * [Azure Private DNS](providers/azure_private_dns.md)
    * [BIND](providers/bind.md)
    * [Bunny DNS](providers/bunny\_dns.md)
    * [Cloudflare](providers/cloudflareapi.md)
    * [ClouDNS](providers/cloudns.md)
    * [CSC Global](providers/cscglobal.md)
    * [deSEC](providers/desec.md)
    * [DigitalOcean](providers/digitalocean.md)
    * [DNS Made Easy](providers/dnsmadeeasy.md)
    * [DNSimple](providers/dnsimple.md)
    * [DNS-over-HTTPS](providers/dnsoverhttps.md)
    * [DOMAINNAMESHOP](providers/domainnameshop.md)
    * [Dynadot](providers/dynadot.md)
    * [easyname](providers/easyname.md)
    * [Exoscale](providers/exoscale.md)
    * [Gandi_v5](providers/gandi_v5.md)
    * [Gcore](providers/gcore.md)
    * [Google Cloud DNS](providers/gcloud.md)
    * [Hetzner DNS Console](providers/hetzner.md)
    * [HEXONET](providers/hexonet.md)
    * [hosting.de](providers/hostingde.md)
    * [Hurricane Electric DNS](providers/hedns.md)
    * [Internet.bs](providers/internetbs.md)
    * [INWX](providers/inwx.md)
    * [Linode](providers/linode.md)
    * [Loopia](providers/loopia.md)
    * [LuaDNS](providers/luadns.md)
    * [Microsoft DNS Server on Microsoft Windows Server](providers/msdns.md)
    * [Mythic Beasts](providers/mythicbeasts.md)
    * [Namecheap](providers/namecheap.md)
    * [Name.com](providers/namedotcom.md)
    * [Netcup](providers/netcup.md)
    * [Netlify](providers/netlify.md)
    * [NS1](providers/ns1.md)
    * [OpenSRS](providers/opensrs.md)
    * [Oracle Cloud](providers/oracle.md)
    * [OVH](providers/ovh.md)
    * [Packetframe](providers/packetframe.md)
    * [Porkbun](providers/porkbun.md)
    * [PowerDNS](providers/powerdns.md)
    * [Realtime Register](providers/realtimeregister.md)
    * [RWTH DNS-Admin](providers/rwth.md)
    * [SoftLayer DNS](providers/softlayer.md)
    * [TransIP](providers/transip.md)
    * [Vultr](providers/vultr.md)

## Commands

* [preview/push](preview-push.md)
* [check-creds](check-creds.md)
* [get-zones](get-zones.md)
* [get-certs](get-certs.md)
* [fmt](fmt.md)
* [creds.json](creds-json.md)
* [Global Flag](globalflags.md)
* [Disabling Colors](colors.md)

## Advanced features

* [CI/CD example for GitLab](ci-cd-gitlab.md)
* [CLI variables](cli-variables.md)
* [Nameservers and Delegations](nameservers.md)
* [Notifications](notifications.md)
* [Useful code tricks](code-tricks.md)
* [JSON Reports](json-reports.md)

## Developer info

* [Code Style Guide](styleguide-code.md)
* [Documentation Style Guide](styleguide-doc.md)
* [DNSControl is an opinionated system](opinions.md)
* [Writing new DNS providers](writing-providers.md)
* [Creating new DNS Resource Types (rtypes)](adding-new-rtypes.md)
* [Integration Tests](integration-tests.md)
* [Unit Testing DNS Data](unittests.md)
* [Bug Triage Process](bug-triage.md)
* [Bring-Your-Own-Secrets for automated testing](byo-secrets.md)
* [Debugging with dlv](debugging-with-dlv.md)
* [ALIAS Records](alias.md)
* [TXT record testing](testing-txt-records.md)
* [DNS records ordering](ordering.md)

## Release

* [How to build and ship a release](release-engineering.md)
* [Changelog v3.16.0](v316.md)
* [GitHub releases](https://github.com/StackExchange/dnscontrol/releases/latest)
