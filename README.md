# Assembly 코드로 hash변환(32비트 약간 어렵게)
- https://github.com/YoungHaKim7/custom_hashmap

# Result

```bash
$ cargo nextest run
    Finished `test` profile [unoptimized + debuginfo] target(s) in 0.00s
────────────
 Nextest run ID 33e1bf18-86a0-44ce-a53a-3fc5f34dada8 with nextest profile: default
    Starting 14 tests across 2 binaries
        PASS [   0.028s] hashmap_easy_ver::std_hash_test test_contains
        PASS [   0.027s] hashmap_easy_ver::std_hash_test test_insert_and_get
        PASS [   0.028s] hashmap_easy_ver::std_hash_test test_get_mut
        PASS [   0.028s] hashmap_easy_ver::std_hash_test test_chache_size
        PASS [   0.029s] hashmap_easy_ver::std_hash_test test_capacity_of_one
        PASS [   0.029s] hashmap_easy_ver::std_hash_test test_empty
        PASS [   0.031s] hashmap_easy_ver::std_hash_test test_access_updates_lru
        PASS [   0.031s] hashmap_easy_ver::std_hash_test test_insert_update_existing_key
        PASS [   0.022s] hashmap_easy_ver::std_hash_test test_len
        PASS [   0.022s] hashmap_easy_ver::std_hash_test test_is_full
        PASS [   0.021s] hashmap_easy_ver::std_hash_test test_new
        PASS [   0.021s] hashmap_easy_ver::std_hash_test test_lru_eviction
        PASS [   0.021s] hashmap_easy_ver::std_hash_test test_remove
        PASS [   0.020s] hashmap_easy_ver::std_hash_test test_string_keys
────────────
     Summary [   0.051s] 14 tests run: 14 passed, 0 skipped
```

