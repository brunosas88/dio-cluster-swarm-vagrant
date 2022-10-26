# dio-cluster-swarm-vagrant
Definição de cluster por IaC utilizando vagrant.

## Objetivos
1. Vagrantfile com as definições de 4 máquinas virtuais. Uma máquina com o nome de master e as outras com os nomes de node01, node02 e node03;
2. Cada máquina virtual tem um ip fixo;
3. Todas as MV irão possuir o Docker pré-instalado;
4. A máquina com o nome de master será o nó manager do cluster;
5. As demais máquinas serão incluídas no cluster swarm como workers;

## Referência
Projeto modificado de https://github.com/denilsonbonatti/docker-projeto2-cluster, com a adição da quarta máquina virtual node03.
