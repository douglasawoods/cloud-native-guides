FROM ansibleplaybookbundle/apb-base

LABEL "com.redhat.apb.spec"=\
"dmVyc2lvbjogMS4wCm5hbWU6IGNsb3VkbmF0aXZlLXdvcmtzaG9wLWFwYgpkZXNjcmlwdGlvbjog\
QVBCIHRvIGRlcGxveSByZXF1aXJlZCBpbmZyYSBjb21wb25lbnRzIGZvciB0aGUgQ2xvdWQtTmF0\
aXZlIFdvcmtzaG9wIG9uIGFuIE9wZW5TaGlmdCBjbHVzdGVyCmJpbmRhYmxlOiBGYWxzZQphc3lu\
Yzogb3B0aW9uYWwKdGFnczoKLSB3b3Jrc2hvcAptZXRhZGF0YToKICBkZXBlbmRlbmNpZXM6IFtd\
CiAgZGlzcGxheU5hbWU6ICJDbG91ZC1OYXRpdmUgV29ya3Nob3AgSW5zdGFsbGVyIgogIGxvbmdE\
ZXNjcmlwdGlvbjogIkluc3RhbGxzIHRoZSBsYWIgaW5zdHJ1Y3Rpb25zIGFuZCByZXF1aXJlZCBj\
b21wb25lbnRzIChHaXQgc2VydmVyLCBOZXh1cywgRWNsaXBzZSBDaGUsIGV0YykgZm9yIHJ1bm5p\
bmcgdGhlIENsb3VkLU5hdGl2ZSBXb3Jrc2hvcCBodHRwczovL2dpdGh1Yi5jb20vb3BlbnNoaWZ0\
LWxhYnMvY2xvdWQtbmF0aXZlLWd1aWRlcyIKICBjb25zb2xlLm9wZW5zaGlmdC5pby9pY29uQ2xh\
c3M6ICJwZmljb24gcGZpY29uLXByb2Nlc3MtYXV0b21hdGlvbiIKICBwcm92aWRlckRpc3BsYXlO\
YW1lOiAiUmVkIEhhdCwgSW5jLiIKcGxhbnM6CiAgLSBuYW1lOiBkZWZhdWx0CiAgICBkZXNjcmlw\
dGlvbjogRGVwbG95cyBDbG91ZC1OYXRpdmUgV29ya3Nob3AgSW5mcmFzdHJ1Y3R1cmUKICAgIGZy\
ZWU6IFRydWUKICAgIG1ldGFkYXRhOgogICAgICBkaXNwbGF5TmFtZTogRGVmYXVsdAogICAgcGFy\
YW1ldGVyczoKICAgIC0gbmFtZTogb3BlbnNoaWZ0X3VzZXIKICAgICAgdGl0bGU6IFVzZXJuYW1l\
CiAgICAgIGRlc2NyaXB0aW9uOiBVc2VyIGlzIHJlcXVpcmVkIGZvciBjcmVhdGluZyBwcm9qZWN0\
IGFkbWluIHJlc291cmNlcwogICAgICB0eXBlOiBzdHJpbmcKICAgICAgcmVxdWlyZWQ6IHRydWUK\
ICAgICAgZGlzcGxheV9ncm91cDogT3BlblNoaWZ0IFVzZXIKICAgIC0gbmFtZTogb3BlbnNoaWZ0\
X3Bhc3N3b3JkCiAgICAgIHRpdGxlOiBQYXNzd29yZAogICAgICBkZXNjcmlwdGlvbjogUGFzc3dv\
cmQgaXMgcmVxdWlyZWQgZm9yIGNyZWF0aW5nIHByb2plY3QgYWRtaW4gcmVzb3VyY2VzCiAgICAg\
IHR5cGU6IHN0cmluZwogICAgICByZXF1aXJlZDogdHJ1ZQogICAgICBkaXNwbGF5X3R5cGU6IHBh\
c3N3b3JkCiAgICAgIGRpc3BsYXlfZ3JvdXA6IE9wZW5TaGlmdCBVc2VyCiAgICAtIG5hbWU6IG9w\
ZW5zaGlmdF9tYXN0ZXJfdXJsCiAgICAgIHRpdGxlOiBPcGVuU2hpZnQgTWFzdGVyIFVSTAogICAg\
ICBkZXNjcmlwdGlvbjogVGhlIGFkZHJlc3MgdG8gT3BlblNoaWZ0IG1hc3RlciBVUkwgdG8gYmUg\
ZGlzcGxheWVkIGluIHRoZSBsYWIgZ3VpZGUgdG8gcGFydGljaXBhbnRzCiAgICAgIHR5cGU6IHN0\
cmluZwogICAgICByZXF1aXJlZDogdHJ1ZQogICAgICBkaXNwbGF5X3R5cGU6IHN0cmluZwogICAg\
ICBkaXNwbGF5X2dyb3VwOiBMYWIgR3VpZGUKICAgIC0gbmFtZTogb3BlbnNoaWZ0X3VzZXJfcGFz\
c3dvcmQKICAgICAgdGl0bGU6IE9wZW5TaGlmdCBVc2VyIFBhc3N3b3JkCiAgICAgIGRlc2NyaXB0\
aW9uOiBUaGUgT3BlblNoaWZ0IHBhc3N3b3JkIGZvciBwYXJ0aWNpcGFudHMgdG8gYmUgZGlzcGxh\
eWVkIGluIHRoZSBsYWIgZ3VpZGUgdG8gcGFydGljaXBhbnRzCiAgICAgIHR5cGU6IHN0cmluZwog\
ICAgICByZXF1aXJlZDogdHJ1ZQogICAgICBkaXNwbGF5X3R5cGU6IHN0cmluZwogICAgICB2YWx1\
ZTogInIzZGg0dDEhIgogICAgICBkaXNwbGF5X2dyb3VwOiBMYWIgR3VpZGUKICAgIC0gbmFtZTog\
Z2l0aHViX3JlZgogICAgICB0aXRsZTogR3VpZGVzIEdpdEh1YiBSZWZlcmVuY2UKICAgICAgZGVz\
Y3JpcHRpb246IFRoZSBHaXRIdWIgcmVmZXJlbmNlIGZvciB0aGUgQ2xvdWQtTmF0aXZlIHdvcmtz\
aG9wIGxhYiBndWlkZQogICAgICB0eXBlOiBlbnVtCiAgICAgIGVudW06IFsib2NwLTMuOSIsICJv\
Y3AtMy43Il0KICAgICAgZGVmYXVsdDogb2NwLTMuOQogICAgICByZXF1aXJlZDogdHJ1ZQogICAg\
ICBkaXNwbGF5X3R5cGU6IHNlbGVjdAogICAgICBkaXNwbGF5X2dyb3VwOiBMYWIgR3VpZGUKICAg\
IC0gbmFtZTogcHJvamVjdF9zdWZmaXgKICAgICAgdGl0bGU6IFVzZXIgUHJvamVjdCBTdWZmaXgK\
ICAgICAgZGVzY3JpcHRpb246IFRoZSBwYXR0ZXJuIHVzZWQgaW4gdGhlIGxhYiBndWlkZSB0byBz\
aG93IHRoZSB1c2VyIHByb2plY3RzIGUuZy4gY29vbHN0b3JlLVhYIAogICAgICB0eXBlOiBzdHJp\
bmcKICAgICAgZGVmYXVsdDogIi1YWCIKICAgICAgcmVxdWlyZWQ6IHRydWUKICAgICAgZGlzcGxh\
eV9ncm91cDogTGFiIEd1aWRlCiAgICAtIG5hbWU6IGdvZ3NfYWRtX3VzZXIKICAgICAgdGl0bGU6\
IEdvZ3MgQWRtaW4gVXNlcgogICAgICBkZXNjcmlwdGlvbjogQWRtaW4gdXNlciBmb3IgR29ncyBH\
aXQgU2VydmVyCiAgICAgIHR5cGU6IHN0cmluZwogICAgICBkZWZhdWx0OiAiZ29ncyIKICAgICAg\
cmVxdWlyZWQ6IHRydWUKICAgICAgZGlzcGxheV9ncm91cDogR2l0IFNlcnZlcgogICAgLSBuYW1l\
OiBnb2dzX2Rldl91c2VyCiAgICAgIHRpdGxlOiBHb2dzIFVzZXIKICAgICAgZGVzY3JpcHRpb246\
IFVzZXIgZm9yIEdvZ3MgR2l0IFNlcnZlcgogICAgICB0eXBlOiBzdHJpbmcKICAgICAgZGVmYXVs\
dDogImRldmVsb3BlciIKICAgICAgcmVxdWlyZWQ6IHRydWUKICAgICAgZGlzcGxheV9ncm91cDog\
R2l0IFNlcnZlcgogICAgLSBuYW1lOiBnb2dzX3B3ZAogICAgICB0aXRsZTogR29ncyBQYXNzd29y\
ZAogICAgICBkZXNjcmlwdGlvbjogUGFzc3dvcmQgZm9yIEdvZ3MgYWRtaW4gdXNlciBhbmQgbm9y\
bWFsIHVzZXIKICAgICAgdHlwZTogc3RyaW5nCiAgICAgIGRlZmF1bHQ6ICJvcGVuc2hpZnQiCiAg\
ICAgIHJlcXVpcmVkOiB0cnVlCiAgICAgIGRpc3BsYXlfZ3JvdXA6IEdpdCBTZXJ2ZXI="

COPY playbooks /opt/apb/actions
ADD requirements.yml /opt/apb/actions/requirements.yml
RUN ansible-galaxy install -r /opt/apb/actions/requirements.yml -f
RUN chmod -R g=u /opt/{ansible,apb}
USER apb
