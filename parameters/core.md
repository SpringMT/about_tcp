ls /proc/sys/net/core/ でとれた内容

parameter | 値 |  説明
----|-----|----
bpf_jit_enable | |
bpf_jit_harden | |
bpf_jit_kallsyms | |
bpf_jit_limit | |
busy_poll | |
busy_read | |
default_qdisc | |
dev_weight | |
dev_weight_rx_bias | |
dev_weight_tx_bias | |
flow_limit_cpu_bitmap | |
flow_limit_table_len | |
max_skb_frags | |
message_burst | |
message_cost | |
netdev_budget | |
netdev_budget_usecs | |
netdev_max_backlog | |
netdev_rss_key | |
netdev_tstamp_prequeue | |
optmem_max | |
rmem_default | rmemはreceive（read）bufferの大きさ |
rmem_max | rmemはreceive（read）bufferの大きさ |
rps_sock_flow_entries | |
somaxconn | |
tstamp_allow_data | |
warnings | |
wmem_default | wmemはsend（write）buffer |
wmem_max | wmemはsend（write）buffer |
xfrm_acq_expires | |
xfrm_aevent_etime | |
xfrm_aevent_rseqth | |
xfrm_larval_drop | |

### 参考
* [LinuxサーバーのTCPネットワークのパフォーマンスを決定するカーネルパラメータ – 3編](https://meetup-jp.toast.com/1516)
