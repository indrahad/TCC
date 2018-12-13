<h1>Infrastructur as a Code </h1>

Infrastruktur sebagai kode (IaC) adalah proses mengelola dan menyediakan pusat data komputer melalui file definisi yang dapat dibaca mesin, daripada konfigurasi perangkat keras fisik atau alat konfigurasi interaktif

Infrastruktur TI yang dikelola oleh ini terdiri dari kedua peralatan fisik seperti server bare-metal serta mesin virtual dan sumber daya konfigurasi terkait. Definisi mungkin dalam sistem kontrol versi. Ia dapat menggunakan skrip atau definisi deklaratif, bukan proses manual, tetapi istilah ini lebih sering digunakan untuk mempromosikan pendekatan deklaratif.

<h3> 15 Infrastructure as Code tools </h3>
- Terraform </br>
- AWS CloudFondation </br>
- Azure Resource Manager and Google Cloud Deployment Manager </br>
- Chef </br>
- Puppet </br>
- Saltstack </br>
- Ansible </br>
- Juju </br>
- Docker </br>
- Vagrant </br>
- Pallet </br>
- (R)?ex </br>
- CFEngine </br>
- NixOS </br>
- Conclusion </br>

<h3> Configuring Ubuntu with Ansible </h3>
Creating an inventory
echo "[group1]" > myhosts

Menambahkan host ke Group
echo "host01 ansible_ssh_user=ubuntu" >> myhosts

periksa tanggal dan waktu saat ini dari host jarak jauh:
ansible group1 -i myhosts -m command -a date

