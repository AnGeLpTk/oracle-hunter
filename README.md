# oracle-hunter

Workflow do GitHub Actions que tenta criar uma VM Always Free (Ampere A1) na Oracle Cloud
até conseguir: cria com 1 OCPU / 6 GB e depois tenta aumentar para 2 OCPU / 12 GB.
Avisa por issue e se desliga ao terminar. Credenciais só em GitHub Secrets.
