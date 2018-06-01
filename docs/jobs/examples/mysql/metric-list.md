# Collected MySQL Server Metrics

## MySQL server performance

```css
mysql.global_status.aborted_clients
mysql.global_status.aborted_connects
mysql.global_status.binlog_cache_disk_use
mysql.global_status.binlog_cache_use
mysql.global_status.binlog_stmt_cache_disk_use
mysql.global_status.binlog_stmt_cache_use
mysql.global_status.bytes_received
mysql.global_status.bytes_sent
mysql.global_status.com_stmt_reprepare
mysql.global_status.connection_errors_accept
mysql.global_status.connection_errors_internal
mysql.global_status.connection_errors_max_connections
mysql.global_status.connection_errors_peer_address
mysql.global_status.connection_errors_select
mysql.global_status.connection_errors_tcpwrap
mysql.global_status.connections
mysql.global_status.created_tmp_disk_tables
mysql.global_status.created_tmp_files
mysql.global_status.created_tmp_tables
mysql.global_status.delayed_errors
mysql.global_status.delayed_insert_threads
mysql.global_status.delayed_writes
mysql.global_status.flush_commands
mysql.global_status.handler_commit
mysql.global_status.handler_delete
mysql.global_status.handler_discover
mysql.global_status.handler_external_lock
mysql.global_status.handler_mrr_init
mysql.global_status.handler_prepare
mysql.global_status.handler_read_first
mysql.global_status.handler_read_key
mysql.global_status.handler_read_last
mysql.global_status.handler_read_next
mysql.global_status.handler_read_prev
mysql.global_status.handler_read_rnd
mysql.global_status.handler_read_rnd_next
mysql.global_status.handler_rollback
mysql.global_status.handler_savepoint
mysql.global_status.handler_savepoint_rollback
mysql.global_status.handler_update
mysql.global_status.handler_write
mysql.global_status.innodb_available_undo_logs
mysql.global_status.innodb_buffer_pool_bytes_data
mysql.global_status.innodb_buffer_pool_bytes_dirty
mysql.global_status.innodb_buffer_pool_pages_data
mysql.global_status.innodb_buffer_pool_pages_dirty
mysql.global_status.innodb_buffer_pool_pages_flushed
mysql.global_status.innodb_buffer_pool_pages_free
mysql.global_status.innodb_buffer_pool_pages_misc
mysql.global_status.innodb_buffer_pool_pages_total
mysql.global_status.innodb_buffer_pool_read_ahead
mysql.global_status.innodb_buffer_pool_read_ahead_evicted
mysql.global_status.innodb_buffer_pool_read_ahead_rnd
mysql.global_status.innodb_buffer_pool_read_requests
mysql.global_status.innodb_buffer_pool_reads
mysql.global_status.innodb_buffer_pool_wait_free
mysql.global_status.innodb_buffer_pool_write_requests
mysql.global_status.innodb_data_fsyncs
mysql.global_status.innodb_data_pending_fsyncs
mysql.global_status.innodb_data_pending_reads
mysql.global_status.innodb_data_pending_writes
mysql.global_status.innodb_data_read
mysql.global_status.innodb_data_reads
mysql.global_status.innodb_data_writes
mysql.global_status.innodb_data_written
mysql.global_status.innodb_dblwr_pages_written
mysql.global_status.innodb_dblwr_writes
mysql.global_status.innodb_log_waits
mysql.global_status.innodb_log_write_requests
mysql.global_status.innodb_log_writes
mysql.global_status.innodb_num_open_files
mysql.global_status.innodb_os_log_fsyncs
mysql.global_status.innodb_os_log_pending_fsyncs
mysql.global_status.innodb_os_log_pending_writes
mysql.global_status.innodb_os_log_written
mysql.global_status.innodb_page_size
mysql.global_status.innodb_pages_created
mysql.global_status.innodb_pages_read
mysql.global_status.innodb_pages_written
mysql.global_status.innodb_row_lock_current_waits
mysql.global_status.innodb_row_lock_time
mysql.global_status.innodb_row_lock_time_avg
mysql.global_status.innodb_row_lock_time_max
mysql.global_status.innodb_row_lock_waits
mysql.global_status.innodb_rows_deleted
mysql.global_status.innodb_rows_inserted
mysql.global_status.innodb_rows_read
mysql.global_status.innodb_rows_updated
mysql.global_status.innodb_truncated_status_writes
mysql.global_status.key_blocks_not_flushed
mysql.global_status.key_blocks_unused
mysql.global_status.key_blocks_used
mysql.global_status.key_read_requests
mysql.global_status.key_reads
mysql.global_status.key_write_requests
mysql.global_status.key_writes
mysql.global_status.locked_connects
mysql.global_status.max_execution_time_exceeded
mysql.global_status.max_execution_time_set
mysql.global_status.max_execution_time_set_failed
mysql.global_status.max_used_connections
mysql.global_status.not_flushed_delayed_rows
mysql.global_status.ongoing_anonymous_transaction_count
mysql.global_status.open_files
mysql.global_status.open_streams
mysql.global_status.open_table_definitions
mysql.global_status.open_tables
mysql.global_status.opened_files
mysql.global_status.opened_table_definitions
mysql.global_status.opened_tables
mysql.global_status.performance_schema_accounts_lost
mysql.global_status.performance_schema_cond_classes_lost
mysql.global_status.performance_schema_cond_instances_lost
mysql.global_status.performance_schema_digest_lost
mysql.global_status.performance_schema_file_classes_lost
mysql.global_status.performance_schema_file_handles_lost
mysql.global_status.performance_schema_file_instances_lost
mysql.global_status.performance_schema_hosts_lost
mysql.global_status.performance_schema_index_stat_lost
mysql.global_status.performance_schema_locker_lost
mysql.global_status.performance_schema_memory_classes_lost
mysql.global_status.performance_schema_metadata_lock_lost
mysql.global_status.performance_schema_mutex_classes_lost
mysql.global_status.performance_schema_mutex_instances_lost
mysql.global_status.performance_schema_nested_statement_lost
mysql.global_status.performance_schema_prepared_statements_lost
mysql.global_status.performance_schema_program_lost
mysql.global_status.performance_schema_rwlock_classes_lost
mysql.global_status.performance_schema_rwlock_instances_lost
mysql.global_status.performance_schema_session_connect_attrs_lost
mysql.global_status.performance_schema_socket_classes_lost
mysql.global_status.performance_schema_socket_instances_lost
mysql.global_status.performance_schema_stage_classes_lost
mysql.global_status.performance_schema_statement_classes_lost
mysql.global_status.performance_schema_table_handles_lost
mysql.global_status.performance_schema_table_instances_lost
mysql.global_status.performance_schema_table_lock_stat_lost
mysql.global_status.performance_schema_thread_classes_lost
mysql.global_status.performance_schema_thread_instances_lost
mysql.global_status.performance_schema_users_lost
mysql.global_status.prepared_stmt_count
mysql.global_status.qcache_free_blocks
mysql.global_status.qcache_free_memory
mysql.global_status.qcache_hits
mysql.global_status.qcache_inserts
mysql.global_status.qcache_lowmem_prunes
mysql.global_status.qcache_not_cached
mysql.global_status.qcache_queries_in_cache
mysql.global_status.qcache_total_blocks
mysql.global_status.queries
mysql.global_status.questions
mysql.global_status.select_full_join
mysql.global_status.select_full_range_join
mysql.global_status.select_range
mysql.global_status.select_range_check
mysql.global_status.select_scan
mysql.global_status.slave_open_temp_tables
mysql.global_status.slow_launch_threads
mysql.global_status.slow_queries
mysql.global_status.sort_merge_passes
mysql.global_status.sort_range
mysql.global_status.sort_rows
mysql.global_status.sort_scan
mysql.global_status.ssl_accept_renegotiates
mysql.global_status.ssl_accepts
mysql.global_status.ssl_callback_cache_hits
mysql.global_status.ssl_cipher
mysql.global_status.ssl_cipher_list
mysql.global_status.ssl_client_connects
mysql.global_status.ssl_connect_renegotiates
mysql.global_status.ssl_ctx_verify_depth
mysql.global_status.ssl_ctx_verify_mode
mysql.global_status.ssl_default_timeout
mysql.global_status.ssl_finished_accepts
mysql.global_status.ssl_finished_connects
mysql.global_status.ssl_session_cache_hits
mysql.global_status.ssl_session_cache_misses
mysql.global_status.ssl_session_cache_overflows
mysql.global_status.ssl_session_cache_size
mysql.global_status.ssl_session_cache_timeouts
mysql.global_status.ssl_sessions_reused
mysql.global_status.ssl_used_session_cache_entries
mysql.global_status.ssl_verify_depth
mysql.global_status.ssl_verify_mode
mysql.global_status.ssl_version
mysql.global_status.table_locks_immediate
mysql.global_status.table_locks_waited
mysql.global_status.table_open_cache_hits
mysql.global_status.table_open_cache_misses
mysql.global_status.table_open_cache_overflows
mysql.global_status.tc_log_max_pages_used
mysql.global_status.tc_log_page_size
mysql.global_status.tc_log_page_waits
mysql.global_status.threads_cached
mysql.global_status.threads_connected
mysql.global_status.threads_created
mysql.global_status.threads_running
mysql.global_status.uptime
mysql.global_status.uptime_since_flush_status
```