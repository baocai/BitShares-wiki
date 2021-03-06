+>> help
+
+clear_console
+[command_name]? (alias for: help [command_name])
+about
+approve_register_account <account_salt> <paying_account_name>
+batch <method_name> <parameters_list>
+blockchain_broadcast_transaction <trx>
+blockchain_calculate_debt <asset> [include_interest]
+blockchain_calculate_supply <asset>
+blockchain_dump_state <path>
+blockchain_export_fork_graph [start_block] [end_block] [filename]
+blockchain_generate_snapshot <filename>
+blockchain_get_account <account>
+blockchain_get_account_public_balance <account_name>
+blockchain_get_account_wall [account_name]
+blockchain_get_asset <asset>
+blockchain_get_balance <owner_address>
+blockchain_get_block <block>
+blockchain_get_block_count
+blockchain_get_block_hash <block_number>
+blockchain_get_block_signee <block>
+blockchain_get_block_transactions <block>
+blockchain_get_delegate_slot_records <delegate_name> [start_block_num] [count]
+blockchain_get_edges <from> [to] [name]
+blockchain_get_feeds_for_asset <asset>
+blockchain_get_feeds_from_delegate <delegate_name>
+blockchain_get_info
+blockchain_get_object <id>
+blockchain_get_security_state
+blockchain_get_transaction <transaction_id_prefix> [exact]
+blockchain_is_synced
+blockchain_list_accounts [first_account_name] [limit]
+blockchain_list_active_delegates [first] [count]
+blockchain_list_address_balances <addr> [chanced_since]
+blockchain_list_address_transactions <addr> [filter_before]
+blockchain_list_assets [first_symbol] [limit]
+blockchain_list_balances [first_balance_id] [limit]
+blockchain_list_blocks [first_block_number] [limit]
+blockchain_list_delegates [first] [count]
+blockchain_list_feed_prices
+blockchain_list_forks
+blockchain_list_key_balances <key>
+blockchain_list_market_transactions <block_number>
+blockchain_list_markets
+blockchain_list_missing_block_delegates <block_number>
+blockchain_list_pending_transactions
+blockchain_list_recently_registered_accounts
+blockchain_list_recently_updated_accounts
+blockchain_market_get_asset_collateral <symbol>
+blockchain_market_list_asks <quote_symbol> <base_symbol> [limit]
+blockchain_market_list_bids <quote_symbol> <base_symbol> [limit]
+blockchain_market_list_covers <quote_symbol> [limit]
+blockchain_market_list_shorts <quote_symbol> [limit]
+blockchain_market_order_book <quote_symbol> <base_symbol> [limit]
+blockchain_market_order_history <quote_symbol> <base_symbol> [skip_count] [limit] [owner]
+blockchain_market_price_history <quote_symbol> <base_symbol> <start_time> <duration> [granularity]
+blockchain_market_status <quote_symbol> <base_symbol>
+blockchain_median_feed_price <symbol>
+blockchain_unclaimed_genesis
+blockchain_verify_signature <signer> <hash> <signature>
+builder_finalize_and_sign <builder>
+debug_advance_time <delta_time_seconds> [unit]
+debug_clear_errors [start_time] [first_error_number] [limit]
+debug_deterministic_private_keys [start] [count] [prefix] [import] [account_name] [create_new_account] [rescan]
+debug_enable_output <enable_flag>
+debug_filter_output_for_tests <enable_flag>
+debug_get_call_statistics
+debug_get_client_name
+debug_list_errors [first_error_number] [limit] [filename]
+debug_list_errors_brief [first_error_number] [limit] [filename]
+debug_start_simulated_time <new_simulated_time>
+debug_update_logging_config
+debug_verify_delegate_votes
+debug_wait <wait_time>
+debug_wait_block_interval <wait_time_in_block_intervals>
+debug_wait_for_block_by_number <block_number> [type]
+debug_write_errors_to_file [path] [start_time]
+delegate_blacklist_add_operation <id>
+delegate_blacklist_add_transaction <id>
+delegate_blacklist_remove_operation <id>
+delegate_blacklist_remove_transaction <id>
+delegate_get_config
+delegate_set_block_max_production_time <time>
+delegate_set_block_max_size <size>
+delegate_set_block_max_transaction_count <count>
+delegate_set_network_min_connection_count <count>
+delegate_set_transaction_canonical_signatures_required <required>
+delegate_set_transaction_max_size <size>
+delegate_set_transaction_min_fee <fee>
+disk_usage
+execute_command_line <input>
+execute_script <script>
+get_info
+get_registration_requests
+help [command_name]
+http_start_server [port]
+mail_archive_message <message_id>
+mail_cancel_message <message_id>
+mail_check_new_messages [get_old_messages]
+mail_fetch_inventory <owner> <start_time> [limit]
+mail_fetch_message <inventory_id>
+mail_get_archive_messages
+mail_get_message <message_id>
+mail_get_messages_from <sender>
+mail_get_messages_in_conversation <account_one> <account_two>
+mail_get_messages_to <recipient>
+mail_get_processing_messages
+mail_inbox
+mail_remove_message <message_id>
+mail_retry_send <message_id>
+mail_send <from> <to> <subject> <body> [reply_to]
+mail_store_message <message>
+meta_help
+network_add_node <node> [command]
+network_broadcast_transaction <transaction_to_broadcast>
+network_get_advanced_node_parameters
+network_get_block_propagation_data <block_hash>
+network_get_connection_count
+network_get_info
+network_get_peer_info [not_firewalled]
+network_get_transaction_propagation_data <transaction_id>
+network_get_upnp_info
+network_get_usage_stats
+network_list_potential_peers
+network_set_advanced_node_parameters <params>
+network_set_allowed_peers <allowed_peers>
+ntp_update_time
+request_register_account <account>
+rpc_set_password [password]
+rpc_set_username [username]
+rpc_start_server [port]
+stop
+validate_address <address>
+wallet_account_balance [account_name]
+wallet_account_balance_extended [account_name]
+wallet_account_balance_ids [account_name]
+wallet_account_create <account_name> [private_data]
+wallet_account_list_public_keys <account_name>
+wallet_account_order_list [account_name] [limit]
+wallet_account_register <account_name> <pay_from_account> [public_data] [delegate_pay_rate] [account_type]
+wallet_account_rename <current_account_name> <new_account_name>
+wallet_account_retract <account_to_retract> <pay_from_account>
+wallet_account_set_approval <account_name> [approval]
+wallet_account_set_favorite <account_name> [is_favorite]
+wallet_account_transaction_history [account_name] [asset_symbol] [limit] [start_block_num] [end_block_num]
+wallet_account_update_active_key <account_to_update> <pay_from_account> [new_active_key]
+wallet_account_update_private_data <account_name> [private_data]
+wallet_account_update_registration <account_name> <pay_from_account> [public_data] [delegate_pay_rate]
+wallet_account_vote_summary [account_name]
+wallet_account_yield [account_name]
+wallet_add_contact_account <account_name> <account_key>
+wallet_add_transaction_note_experimental <transaction_id> <note>
+wallet_address_create <account_name> [label] [legacy_network_byte]
+wallet_asset_authorize_key <paying_account> <symbol> <address> [meta]
+wallet_asset_create <symbol> <asset_name> <issuer_name> <description> <maximum_share_supply> <precision> [public_data] [is_market_issued]
+wallet_asset_issue <amount> <symbol> <to_account_name> [memo_message]
+wallet_asset_update <symbol> [name] [description] [public_data] [maximum_share_supply] [precision] [issuer_transaction_fee] [flags] [issuer_permissions] [issuer_account_name] [required_sigs] [authority]
+wallet_backup_create <json_filename>
+wallet_backup_restore <json_filename> <wallet_name> <imported_wallet_passphrase>
+wallet_balance_set_vote_info <balance_id> [voter_address] [vote_method] [sign_and_broadcast] [builder_path]
+wallet_builder_add_signature <builder> [broadcast] [builder_path]
+wallet_builder_file_add_signature [broadcast] [builder_path]
+wallet_burn <amount_to_burn> <asset_symbol> <from_account_name> <for_or_against> <to_account_name> [public_message] [anonymous]
+wallet_change_passphrase <passphrase>
+wallet_check_sharedrop
+wallet_check_vote_proportion <account>
+wallet_close
+wallet_collect_genesis_balances <account_name>
+wallet_collect_vested_balances <account_name>
+wallet_create <wallet_name> <new_passphrase> [brain_key]
+wallet_delegate_set_block_production <delegate_name> <enabled>
+wallet_delegate_update_signing_key <authorizing_account_name> <delegate_name> <signing_key>
+wallet_delegate_withdraw_pay <delegate_name> <to_account_name> <amount_to_withdraw>
+wallet_dump_private_key <input>
+wallet_escrow_summary [account_name]
+wallet_generate_brain_seed
+wallet_get_account <account_name>
+wallet_get_account_public_address <account_name>
+wallet_get_info
+wallet_get_name
+wallet_get_pending_transaction_errors [filename]
+wallet_get_setting <name>
+wallet_get_transaction <transaction_id>
+wallet_get_transaction_fee [symbol]
+wallet_import_bitcoin <wallet_filename> <passphrase> <account_name>
+wallet_import_electrum <wallet_filename> <passphrase> <account_name>
+wallet_import_keyhotee <firstname> <middlename> <lastname> <brainkey> <keyhoteeid>
+wallet_import_keys_from_json <json_filename> <imported_wallet_passphrase> <account>
+wallet_import_private_key <wif_key> [account_name] [create_new_account] [rescan]
+wallet_list
+wallet_list_accounts
+wallet_list_favorite_accounts
+wallet_list_my_accounts
+wallet_list_unregistered_accounts
+wallet_lock
+wallet_login_finish <server_key> <client_key> <client_signature>
+wallet_login_start <server_account>
+wallet_mail_create <sender> <subject> <body> [reply_to]
+wallet_mail_encrypt <recipient> <plaintext>
+wallet_mail_open <recipient> <ciphertext>
+wallet_market_add_collateral <from_account_name> <cover_id> <real_quantity_collateral_to_add>
+wallet_market_batch_update <cancel_order_ids> <new_orders> <sign>
+wallet_market_cancel_order <order_id>
+wallet_market_cancel_orders <order_ids>
+wallet_market_cover <from_account_name> <quantity> <quantity_symbol> <cover_id>
+wallet_market_order_list <base_symbol> <quote_symbol> [limit] [account_name]
+wallet_market_submit_ask <from_account_name> <sell_quantity> <sell_quantity_symbol> <ask_price> <ask_price_symbol> [allow_stupid_ask]
+wallet_market_submit_bid <from_account_name> <quantity> <quantity_symbol> <base_price> <base_symbol> [allow_stupid_bid]
+wallet_market_submit_relative_ask <from_account_name> <sell_quantity> <sell_quantity_symbol> <relative_ask_price> <ask_price_symbol> [limit_ask_price]
+wallet_market_submit_relative_bid <from_account_name> <quantity> <quantity_symbol> <relative_price> <base_symbol> [limit_price]
+wallet_market_submit_short <from_account_name> <short_collateral> <collateral_symbol> <interest_rate> <quote_symbol> [short_price_limit]
+wallet_multisig_deposit <amount> <symbol> <from_name> <m> <addresses> [vote_method]
+wallet_multisig_get_balance_id <m> <addresses>
+wallet_multisig_withdraw_start <amount> <symbol> <from> <to_address> [vote_method] [builder_path]
+wallet_object_create <account> [user_data] [m] [owners]
+wallet_object_list <account>
+wallet_object_transfer <paying_account_name> <object_id> <m> <owners> [sign_and_broadcast]
+wallet_object_update <paying_account_name> <object_id> [user_data] [sign_and_broadcast]
+wallet_open <wallet_name>
+wallet_publish_feeds <delegate_account> <symbol_to_price_map>
+wallet_publish_feeds_multi_experimental <symbol_to_price_map>
+wallet_publish_price_feed <delegate_account> <price> <asset_symbol>
+wallet_publish_slate <publishing_account_name> [paying_account_name]
+wallet_publish_version <publishing_account_name> [paying_account_name]
+wallet_rebroadcast_transaction <transaction_id>
+wallet_recover_accounts <accounts_to_recover> [maximum_number_of_attempts]
+wallet_recover_transaction <transaction_id_prefix> [recipient_account]
+wallet_regenerate_keys <account_name> <max_key_number>
+wallet_release_escrow <pay_fee_with_account_name> <escrow_balance_id> <released_by_account> [amount_to_sender] [amount_to_receiver]
+wallet_remove_contact_account <account_name>
+wallet_remove_transaction <transaction_id>
+wallet_repair_records [collecting_account_name]
+wallet_rescan_blockchain [first_block_number] [num_blocks] [fast_scan]
+wallet_scan_transaction <transaction_id> [overwrite_existing]
+wallet_scan_transaction_experimental <transaction_id> [overwrite_existing]
+wallet_set_automatic_backups <enabled>
+wallet_set_edge <paying_account> <from> <to> <name> <value>
+wallet_set_preferred_mail_servers <account_name> <server_list> [paying_account]
+wallet_set_setting <name> <value>
+wallet_set_transaction_expiration_time <seconds>
+wallet_set_transaction_fee <fee>
+wallet_set_transaction_scanning <enabled>
+wallet_sign_hash <signer> <hash>
+wallet_transaction_history_experimental [account_name]
+wallet_transfer <amount_to_transfer> <asset_symbol> <from_account_name> <to_account_name> [memo_message] [vote_method]
+wallet_transfer_from <amount_to_transfer> <asset_symbol> <paying_account_name> <from_account_name> <to_account_name> [memo_message] [vote_method]
+wallet_transfer_from_with_escrow <amount_to_transfer> <asset_symbol> <paying_account_name> <from_account_name> <to_account_name> <escrow_account_name> [agreement] [memo_message] [vote_method]
+wallet_transfer_to_address <amount_to_transfer> <asset_symbol> <from_account_name> <to_address> [memo_message] [vote_method]
+wallet_transfer_to_legacy_address <amount_to_transfer> <asset_symbol> <from_account_name> <to_address> [memo_message] [vote_method]
+wallet_transfer_to_public_account <amount_to_transfer> <asset_symbol> <from_account_name> <to_account_name> [memo_message] [vote_method]
+wallet_unlock <timeout> <passphrase>
+wallet_verify_titan_deposit <transaction_id_prefix>
+wallet_withdraw_from_address <amount> <symbol> <from_address> <to> [vote_method] [sign_and_broadcast] [builder_path]
+wallet_withdraw_from_legacy_address <amount> <symbol> <from_address> <to> [vote_method] [sign_and_broadcast] [builder_path]