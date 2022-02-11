とりあえず parameterを調べて残しておく

ls /proc/sys/net/ipv4/tcp_* でとれた内容

parameter | 値 |  説明
----|-----|----
tcp_abort_on_overflow | |
tcp_adv_win_scale | |
tcp_allowed_congestion_control | |
tcp_app_win | |
tcp_autocorking | |
tcp_available_congestion_control | |
tcp_available_ulp | |
tcp_base_mss | |
tcp_challenge_ack_limit | |
tcp_congestion_control | |
tcp_dsack | |
tcp_early_demux | |
tcp_early_retrans | |
tcp_ecn | |
tcp_ecn_fallback | |
tcp_fack | |
tcp_fastopen | |
tcp_fastopen_blackhole_timeout_sec | |
tcp_fastopen_key | |
tcp_fin_timeout | |
tcp_frto | |
tcp_fwmark_accept | |
tcp_invalid_ratelimit | |
tcp_keepalive_intvl | | keepalive packetを送信する間隔を秒単位で指定
tcp_keepalive_probes | | keepalive packetを送信する回数。　この回数だけ試しても接続先から反応が得られない場合は、 あきらめて接続を切断する。
tcp_keepalive_time | | keepalive packetを送信するまでの時間を秒単位で指定
tcp_l3mdev_accept | |
tcp_limit_output_bytes | |
tcp_low_latency | |
tcp_max_orphans  | |
tcp_max_reordering | |
tcp_max_syn_backlog | |
tcp_max_tw_buckets | |
tcp_mem | カーネルでTCP用に使用できるメモリサイズ |
tcp_min_rtt_wlen | |
tcp_min_snd_mss | |
tcp_min_tso_segs | |
tcp_moderate_rcvbuf | |
tcp_mtu_probing | |
tcp_no_metrics_save | |
tcp_notsent_lowat | |
tcp_orphan_retries | |
tcp_pacing_ca_ratio | |
tcp_pacing_ss_ratio | |
tcp_probe_interval | |
tcp_probe_threshold | |
tcp_recovery | |
tcp_reordering | |
tcp_retrans_collapse | |
tcp_retries1 | |
tcp_retries2 | |
tcp_rfc1337 | |
tcp_rmem | |
tcp_sack | |
tcp_slow_start_after_idle | |
tcp_stdurg | |
tcp_syn_retries | |
tcp_synack_retries | |
tcp_syncookies | |
tcp_thin_linear_timeouts | |
tcp_timestamps | |
tcp_tso_win_divisor | |
tcp_tw_reuse | | バージョン4.12から廃止
tcp_window_scaling | |
tcp_wmem | |
tcp_workaround_signed_windows | |

### 参考
* [LinuxサーバーのTCPネットワークのパフォーマンスを決定するカーネルパラメータ – 3編](https://meetup-jp.toast.com/1516
* https://linuxjm.osdn.jp/html/LDP_man-pages/man7/tcp.7.html
* [net.ipv4.tcp_tw_recycle は廃止されました ― その危険性を理解する](https://qiita.com/tmshn/items/b49f1b51bfc472968b30)
