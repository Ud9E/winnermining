test__all__.py
#uses socket test__api.py
test__api_timeout.py
test__ares_host_result.py
test__ares_timeout.py  # explicitly uses ares resolver
# uses socket test__backdoor.py
test__close_backend_fd.py
test__core_async.py
test__core_callback.py
test__core_loop_run.py
test__core.py
test__core_stat.py
test__core_timer.py
test__core_watcher.py
test__destroy.py
# uses socket test__doctests.py
test__environ.py
test__event.py
# uses socket test__example_echoserver.py
# uses socket test__example_portforwarder.py
# uses socket test__example_w*.py
# uses bunch of things test__examples.py
# uses socket test__example_udp_client.py
# uses socket test__example_udp_server.py
test__exc_info.py
#test__execmodules.py
test__fileobject.py
# uses socket test__greenio.py
test__GreenletExit.py
test__greenlet.py
test__greenletset.py
# uses socket test__greenness.py
test__hub_join.py
test__hub_join_timeout.py
# uses socket test__hub.py
test__issue112.py
test__issue1864.py
test__joinall.py
test__local.py
test__loop_callback.py
test__memleak.py
# uses lots of things test___monkey_patching.py
test__monkey.py
test__order.py
test__os.py
test__pool.py
# uses socket test__pywsgi.py
test__queue.py
test__monkey_queue.py
# uses socket test__refcount.py
test__select.py
test__semaphore.py
# uses socket test__server.py
# test__server_pywsgi.py
test__signal.py
# uses socket test__socket_close.py
# test__socket_dns6.py
# test__socket_dns.py
# test__socket_errors.py
# test__socket.py
# test__socket_ssl.py
# test__socket_timeout.py
test__subprocess_interrupted.py
test__subprocess.py
test__systemerror.py
test__threading_2.py
test__threading_patched_local.py
test__threading_vs_settrace.py
test__threadpool.py
test__timeout.py
test__compat.py
test__core_fork.py
test__doctests.py
test__core_loop_run_sig_mod.py
test__execmodules.py
test__greenio.py
test__greenness.py
test__hub.py
test__import_blocking_in_greenlet.py
test__import_wait.py
test__issue230.py
test__issue330.py
test__issue467.py

![Image](https://github.com/user-attachments/assets/d7419ec9-dc67-403f-bf28-8faea5f1f74f)
test__issue6.py
test__issue600.py
test__issue607.py
test__issue461_471.py
test__monkey_builtins_future.py
test__monkey_hub_in_thread.py
test__monkey_logging.py
test__monkey_multiple_imports.py
test__monkey_scope.py
test__monkey_selectors.py
test__monkey_sigchld.py
test__monkey_sigchld_2.py
test__nondefaultloop.py
test__monkey_sigchld_3.py
test__real_greenlet.py
test__refcount.py
test__sleep0.py
test__subprocess_poll.py
test__threading.py
test__threading_before_monkey.py
test__threading_holding_lock_while_monkey.py
test__threading_monkey_in_thread.py
test__threading_native_before_monkey.py
test__threadpool_executor_patched.py
# monkey patched standard tests:
test_queue.py
test_select.py
test_signal.py
test_subprocess.py
test_threading_local.py
test_threading.py
test_thread.py
test_selectors.py
test_timeout.py
# test_asyncore probably does use the resolver, but only
# implicitly for localhost, which is covered well enough
# elsewhere that we don't need to spend the 20s (*2)
test_asyncore.py
test___config.py
test__destroy_default_loop.py
test__util.py
test___ident.py
test__issue639.py
test__issue_728.py
test__refcount_core.py
test__api.py
test__monitor.py
test__events.py
test__iwait.py
