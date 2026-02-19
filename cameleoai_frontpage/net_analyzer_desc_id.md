# Net Analyzer - Deskripsi Singkat (Bahasa Indonesia)

Net Analyzer adalah platform analisis PCAP dan aliran data (flow analysis) berkelas forensik yang dibangun untuk kecepatan, kepercayaan, dan eksplanabilitas. Platform ini menggabungkan proses ingesti data berkinerja tinggi (PCAP/CSV/Parquet), telemetri tingkat lanjut (sidik jari JA3/TLS, entropi, deteksi penyimpangan/drift), serta mesin neuro-simbolik hibrida yang memadukan sensor heuristik dengan penalaran Bayesian. Perpaduan ini menghasilkan kesimpulan ancaman yang jelas, dapat diaudit, serta mendukung simulasi "what-if" yang interaktif.

Didukung oleh backend Rust, Net Analyzer menghadirkan pemrosesan yang deterministik dan aman-memori (memory-safe) dengan overhead CPU yang rendah. Hal ini memungkinkan analisis cepat pada data capture berskala besar sekaligus mengurangi risiko crash dan paparan terhadap serangan rantai pasok (supply-chain exposure)—sebuah aspek krusial bagi lingkungan kerja SOC dan CISO.

Setiap artefak dalam platform ini dilindungi dengan rantai bukti (chain-of-custody) SHA-256, fitur redaksi privasi ("Masked Mode"), dan hasil yang terverifikasi secara backend. Dengan demikian, tim keamanan dapat menyelidiki insiden dengan penuh percaya diri, menghasilkan laporan yang memenuhi standar kepatuhan, serta membagikan temuan tanpa mengorbankan integritas atau data sensitif.
